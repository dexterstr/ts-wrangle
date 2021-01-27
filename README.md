# ts-wrangle

## Tarun Sarpanjeri

## Assigned Play

- Twelfth Night
- [Play url](http://shakespeare.mit.edu/twelfth_night/full.html)

## Speakers

- Speaker 1 - VIOLA
- Speaker 2 - SIR TOBY BELCH

## Question

- Who speaks more?

## command used to find number of times speaker1 spoken

tr '[:space:]' '[\n*]' < Data.txt | grep -i -c VIOLA
Result: 137
<br>

[Otput file speaker 1](https://github.com/dexterstr/ts-wrangle/blob/main/viola.txt)

## command used to find number of times speaker2 spoken

tr '[:space:]' '[\n*]' < Data.txt | grep -i -c OLIVIA
Result: 153
<br>

[Otput file speaker 2](https://github.com/dexterstr/ts-wrangle/blob/main/olivia.txt)

## Result

OLIVIA speaks more times than VIOLA.

## input file

[input file](https://github.com/dexterstr/ts-wrangle/blob/main/Data.txt)
<br>

#### other commands

ls | grep -v -r "[a-z]" Data.txt
<br>
tr '[:space:]' '[\n*]' < Data.txt | grep -i -c OLIVIA
<br>

$ tr ' ' '\n' < Data.txt | grep VIOLA | wc -l
