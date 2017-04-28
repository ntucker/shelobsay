# shelobsay

> Tell Shelob what to say

Like [cowsay](http://en.wikipedia.org/wiki/Cowsay), but less cow.


## Install

```
$ yarn add git+ssh://git@github.com/ntucker/shelobsay
```


## Usage

```js
const shelobsay = require('shelobsay');

console.log(shelobsay('Hello, and welcome to my fantastic generator full of whimsy and bubble gum!'));

/*
     \_______/        ╭──────────────────────────╮
 `.,-'\_____/`-.,'    │ Hello, and welcome to my │
  /`..'\ _ /`.,'\     │ fantastic generator full │
 /  /`.,' `.,'\  \    │   of whimsy and bubble   │
/__/__/     \__\__\__ │           gum!           │
\  \  \     /  /  /   ╰──────────────────────────╯
 \  \,'`._,'`./  /
  \,'`./___\,'`./
 ,'`-./_____\,-'`.
     /       \
 */
```

*You can style your text with [`chalk`](https://github.com/sindresorhus/chalk) before passing it to `shelobsay`.*


## CLI

```
$ yarn global add shelobsay
```

```
$ shelobsay --help

  Tell Shelob what to say

  Usage
    $ shelobsay <string>
    $ shelobsay <string> --maxLength 8
    $ echo <string> | shelobsay

  Example
    $ shelobsay 'Sindre is a horse'

     \_______/
 `.,-'\_____/`-.,'
  /`..'\ _ /`.,'\     ╭──────────────────────────╮
 /  /`.,' `.,'\  \    │     Sindre is a horse    │
/__/__/     \__\__\__ ╰──────────────────────────╯
\  \  \     /  /  /
 \  \,'`._,'`./  /
  \,'`./___\,'`./
 ,'`-./_____\,-'`.
     /       \
```


## License

[BSD license](http://opensource.org/licenses/bsd-license.php)
Copyright (c) Robinhood Markets
