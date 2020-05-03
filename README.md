# crouching-tiger-hidden-dragon
a unique name identifier generator


syntax:

flags:
  - **-h** hash output
  - **-i** gaurentee index / 1-to-1 relationship
  

| token type             | syntax                  | output at 2         |
|------------------------|-------------------------|---------------------|
| static text            | 'you\'re'               | you're              |
| word from list         | animal                  | Abyssinian          |
| digit                  | #                       | 2                   |
| repeat 3 or more times | #{3,}                   | 002                 |
| alliteration           | (animal) (gem)          | Aardvark Agate      |
| non-counting token     | [animal]                | Aardvark            |