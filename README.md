<h2  align="center">Random-Math-Question</h2>
<p  align="center">A function that generates a math question</p>

<p align="center">
  <a href="https://github.com/tokyojack/random-math-question/stargazers"><img src="https://img.shields.io/github/stars/tokyojack/random-math-question.svg"></a>
  <a href="https://github.com/tokyojack/random-math-question/issues"><img src="https://img.shields.io/github/issues/tokyojack/random-math-question.svg"></a>
  <a href="https://github.com/tokyojack/random-math-question/network"><img src="https://img.shields.io/github/forks/tokyojack/random-math-question.svg"></a>
  <a href="https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Ftokyojack%2Frandom-math-question"><img src="https://img.shields.io/twitter/url/https/github.com/tokyojack/random-math-question.svg?style=social"></a>
</p>
  
<img align="center" src="https://i.imgur.com/NHNVSHD.png"/>

## :cd: Installation

Simpley run this with-in your console and you're good to go!
```
npm install random-math-question --save
```


## :straight_ruler: Usage

  ```
  var randomMathQuestion = require('random-math-question');
  
  console.log(randomMathQuestion.get()); //Returns a random math questions with random values
  
  console.log(randomMathQuestion.get({
    numberRange: '1-5000',
    amountOfNumber: '5-10',
    operations: ['/', '*', '+', '-'],
    nagative: {
        containsNagatives: true,
        negativeChance: '10%'
    },
    exponent: {
        containsExponents: true,
        exponentChance: '10%',
        exponentRange: '1-10'
    },
})); //Returns a configured random math question
  ```
  
## Author


![Jack Clarke](https://avatars1.githubusercontent.com/u/19690448?s=96&v=4)
---|
Jack Clarke
