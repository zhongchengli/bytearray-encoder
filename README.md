# Programming Exercise - Decoder
### Install Node dependencies
```
$ npm i
```
### Check outdated dependencies
```
$ npm out
```
### Update dependencies
```
$ npm up
```

### How to run
#### 1. compile typescript class
```
$ tsc
```
#### 2. run mocha unit tests
```
$ mocha
```


# Exercise

## Problem:

- [X] Write a function to decode an octal string to a number in an array of bytes. For example,
"31646541" should produce [103, 77, 97].

### Optional
To increase the challenge, consider the following:
1. [X] Write the corresponding encode function
2. [X] Add hexadecimal support
3. [X] Add base32 or base64 support
4. [ ] Use your functions to express a sha1 digest in 24 chars
5. [X] Write a property based test
6. [X] Does it work for octal:

```
116311474231113516702134342400414143206126403671660545535070012425145143
3665154621070427104557201067171276700627170465777043334607301704736021762
6325467150763006577133541526554667660414027165423126701315057614760526500
0452421616177052165224543311447543654741617367042213645643631333465753306
2163564254163664432653550166600433332675642447003252221104064117622317044
717471253
```

