## Hashing

### Topics covered today

* Apology (quiz 2 notifications)
* Homework and review
* What is hashing
* Class exercise
* Quiz

---

### Homework review

Did anyone do any further digging?

Are there any questions over this?

What questions would you NOT want me to ask on a quiz?

---

### What is Hashing?

You guys tell me:

Three Key tenets of a hash algorithm:

1. ?

2. ?

3. ?

What is Hashing used for:

* A one way function that obeys the above three things
* verify the integrity of data (block chain, downloads, git commits, secure software)
* as a part of verifying a given users *Authenticity* (a part of *Authentication*)

---

### Class Exercise

Bogus quiz results are in!

But first, a pet peeve of mine...

[Link to quiz result data](https://raw.githubusercontent.com/mkijowski/ceg3400/master/hashing/data/quiz-data.csv)
`sha256sum : ec39ca84b1ddc4608a161ba8338846b51e5de14cc7f7b8057c61d7b3db8b65b9`

do you trust the above

---

Follow along (in `bash`) for some data science fun:

What is the difference between the following:

* `echo "Hi!"`
* `printf "Hi!"'`  <----- Hint: Use this one for the exercise

What do the following do?

* `|`  The pipe character
* `awk -F ',' '{ print $1 }'`   Hint: pipe the `cat` output of quiz-data.csv into this
* `grep <string>`  

Now about the quiz data, can we reverse our hash?

---

What are some common (semi) unique identifiers for people?

* campus W-number
* campus UID
* Social Security Number
* First initial Last name combo ie: `MKijowski`

---

### There is a quiz covering todays in class exercise and the homework!

Quiz is available till 11:59pm tonight!  One chance only this time!
Take the quiz!
Note: your grade might be low on this one, I may have broken the autograder...

---

[Ugh](https://towardsdatascience.com/anonymizing-data-sets-c4602e581a35)

[Anatomy of a git commit](https://blog.thoughtram.io/git/2014/11/18/the-anatomy-of-a-git-commit.html)

