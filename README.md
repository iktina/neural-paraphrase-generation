# Neural Paraphrase Generation

## Welcome
The service receives a text string and uses them as input to the pre-trained model.

## What’s the point?
The service outputs a text string that is the 10 paraphrased sentences.

## How does it work?
The user must provide the following inputs in order to start the service and get a response:

Inputs:
- ```method```: paraphrase
- ```input_data```: a string containing the origin text

## What to expect from this service?
Input data:

sentence: ```Mama always said life was like a box of chocolates. You never know what you're gonna get.```

answer: 

```Life was like a box of chocolates according to Mama. You don't know what you're going to get.```

```Life was like a box of chocolates. You don't know what you'll get.```

```Mama said life was like a box of chocolates. You don't know what you will get.```

```Life was like a box of chocolates, according to Mama. You never know what you will get.```

```Life was like a box of chocolates according to mama. You never know what you're going to get.```

```Life is like a box of chocolates according to Mama. You never know what you'll get.```

```Life is like a box of chocolates. You don't know what you're gonna get.```

```Life was like a box of chocolates, said Mama. You don't know what you're getting.```

```Life was like a box of chocolates, according to mama. You don't know what you get.```

```Life is like a box of chocolates, according to Mama. You never know what's going to happen.```
