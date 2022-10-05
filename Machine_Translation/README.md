# Machine Translation with transformer (from Persian to English)
Machine Translation task, translate text from one language to another. With the advent of Transformers, Machine translations tasks have been enterd to a new area.
This project is implemented in Pytorch.

## Preprocessing
Several preprocessing method are used:
- creating dictionary for words
- adding some meaningful tokens like <SOS>, <EOF>, <PAD>
- handleing persian unicodes
- removing infrequent tokens 

 After cleaning the data, two different tokenizing method are used in this project:
- tokenizing with NLTK and regex
- Byte Pair Encoding

## Architecture
We implement Encoder part of the Transformer from scratch and use Pytorch Decoder in order to train English text to persian.<br/>
Transformer architecture is visible in the following diagram:


## Training

The implemented network has 3 Encoder moodule and 3 decoder module.<br/>
We compare resualts with three diffierent methods:
  
- model with NLTK tokenizer with normalization layer
- model with NLTK tokenizer without normalization layer
- model with Byte Pair Encoding tokenizer without normalization layer

## resualts

A sample of resualts:
| English      | Persian (translation of model)  |
| ----------- | ----------- |
| I would suggest the flight at a quarter past seven   |      بله ، من پرواز ساعت هفت و ربع را پیشنهاد میکنم   |
| yes . is everything okay so far then    |  بله , پس همه چیز خوب است ? بله .        |
| what is the name of our hotel    | نام ما چیست ?     |
  
