# Pinyin Tone Converter

A simple Javascript plugin to convert pinyin with numbers to tone marks.
This plugin is based on the [Quizlet Pinyin Converter](https://github.com/quizlet/pinyin-converter)

Works in node and in the browser. No external dependencies.

## Installation

`npm install pinyin-tone-converter`

## Usage

```js
import convertPinyinTones from 'pinyin-tone-converter';

convertPinyinTones('ni3hao3');
// returns 'nǐhǎo'

convertPinyinTones('san1ren2xing2bi4you3wo3shi1');
// returns "sānrénxíngbìyǒuwǒshī"

// ü can be typed by using v
convertPinyinTones('lv4');
// returns "lǜ"

// works with uppercase chars too
convertPinyinTones('WO3 HEN3 XI3HUAN QUIZLET!');
// returns "WǑ HĚN XǏHUAN QUIZLET!"
```

## License

pinyin-tone-converter is released under a [MIT License](https://opensource.org/licenses/MIT)

## Contributing

Contributions are welcome! These steps will guide you through contributing to this project:

- Fork the repo
- Clone it and install dependencies

  git clone https://github.com/chanind/pinyin-tone-converter
  yarn install

Make and commit your changes. Make sure the commands yarn run build and yarn run test:prod are working.

Finally send a [GitHub Pull Request](https://github.com/chanind/pinyin-tone-converter/compare?expand=1) with a clear list of what you've done. Make sure all of your commits are atomic (one feature per commit). Please add tests for any features that you add or change.

## Enjoy!
