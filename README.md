# Python Artificial Intelligence

## About

It is use for understing ML, DL, and NLP also you can make small AI chatbot from it

## How to install?

Run the command in your terminal.

```python
pip install git+https://github.com/username/repository.git
```
## How to use?

After installing the package import Brain class from pyai module.

```python
from pyai import Brain
```

## Train Module

To train model write.

```python
model = Brain()
maodel.data('Question', 'It's Answer')
# You can add more data.

# Train Model.

result = model.train()

# Take Questions from the user

while True:
    question = input('Question : ')
    print(f'Answer : {result}')
```
Use this to train you model (Brain of your Chatbot). 

## Make your bot smarter. 

To make your model or bot smarter you have to give him lot of datas, otherwise you can also use HugeBrain from pyai module. where HugeBrain is the class.

```python
from pyai import HugeBrain

model = HugeBrain()

# Give some context to him.

model.context('context') # In any language you want.

# ask some questions.

while True:
    questions = input("Questions: ")
    print(f'Answer : {model.answer(question)}')

```

this can help you to create a intermediate bot.

## Also use built-in Python Artificial Intelligence. 

To create advanced bot you have to get api form the Python Artificial Intelligence official website. 

```link
https://pyai.api.com/get_api
```

First you have to create your api.
After that:

```python
from pyai import AdvanceBrain

api = "your_api_key" # Get it from the link.

model = AdvanceBrain(api)

# main.py

while True:
    question = input("Questions: ")
    print(f"Answer : {model.answer(question)}")

```
This will create you advanced python AI.

