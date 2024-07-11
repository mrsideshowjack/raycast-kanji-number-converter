# Japanese Number Converter

This extension lets you convert japanese kanji symbols for numbers into Number format.

examples:
```
三十 --> 30
35万 --> 350,000
```

Under the hood the value is passed into the package [@geolonia/japanese-numeral
](https://github.com/geolonia/japanese-numeral) and converted with `kanji2number()`

**Why use this over google translate?**

I find myself using this a bit as when you put '三十万' into google translate it will output 'Three hundred thousand' which I almost never need

![image](https://github.com/mrsideshowjack/raycast-kanji-number-converter/assets/9937136/7a44aa86-8e57-4446-a687-f9fee146bf0a)


PR for publishing into raycast https://github.com/raycast/extensions/pull/13420
