# textlint-rule-readable-kanji-balance-ja



## Install

Install with [npm](https://www.npmjs.com/):

    npm install git+https://github.com/guruguruman/textlint-rule-readable-kanji-balance-ja.git

## Usage

Via `.textlintrc`(Recommended)

```json
{
    "rules": {
        "rule-readable-kanji-balance-ja": true
    }
}
```

Via CLI

```
textlint --rule readable-kanji-balance-ja README.md
```

### Build

Builds source codes for publish to the `lib` folder.
You can write ES2015+ source codes in `src/` folder.

    npm run build

### Tests

Run test code in `test` folder.
Test textlint rule by [textlint-tester](https://github.com/textlint/textlint-tester "textlint-tester").

    npm test

## License

ISC © Tomoyuki Kato
