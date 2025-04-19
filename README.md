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
