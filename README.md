A simple example of exporting a [transformer](https://huggingface.co/docs/transformers/index) model with Python, then loading it into tract to make predictions.

# To Use

First export the pre-trained transformer model using Python and PyTorch

``` shell
python export.py
```

the exported model and tokenizer are saved in `./albert`. Then load the model into tract and make prediction.

```shell
CONTENT="My name is Albert and I live in the computer." cargo run --release
>> What is my name?
Answer: Albert
```
