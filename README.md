# number_to_words

 API convert number to words by `localeID`. Now only support English And Malayalam. please contribute  .

## Usage
To use this plugin, add number_to_words as a [dependency in your pubspec.yaml](https://flutter.io/docs/development/packages-and-plugins/using-packages) file.

## Example

At This time (01/may/2021) Package not Updated.So for Null safety problem please Add dependncy in pubsec.yaml

number_to_words:
    git:
      url: git://github.com/RR-Reddy/NumberToWords.git
      ref: master


```
import 'package:number_to_words/number_to_words.dart';

void main() {

  print(NumberToWord().convert('ml',21)); //ഇരുപത്തി ഒന്ന്
  print(NumberToWord().convert('ml',10)); //പത്ത്
  print(NumberToWord().convert('ml',1000)); //ആയിരം

  print(NumberToWord().convert('en-in',1000)); //thousand
  print(NumberToWord().convert('en-in',100)); //hundred
  print(NumberToWord().convert('en-in',10)); //ten
}

```
