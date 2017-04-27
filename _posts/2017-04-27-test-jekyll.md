---
title:        "开始"
description:  "A short description of the page's content"
image:        "http://placehold.it/400x200"
author:       "candyless"
---

An h1 header
============



 *Italic*, **bold**,  `monospace`. 


  * this one
  * that one
  * the other one



> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.



An h2 header
------------

 1. first item
 2. second item
 3. third item

Note again how the actual text starts at 4 columns in (4 characters
from the left side). Here's a code sample:

    # Let me re-iterate ...
    for i in 1 .. 10 { do-something(i) }



~~~
define foobar() {
    print "Welcome to flavor country!";
}
~~~



~~~python
import time
# Quick, count to ten!
for i in range(10):
    # (but not *too* quick)
    time.sleep(0.5)
    print i
~~~



### An h3 header ###



 1. First, get these ingredients:

      * carrots
      * celery
      * lentils

 2. Boil some water.

 3. Dump everything in the pot and follow
    this algorithm:

        find wooden spoon
        uncover pot
        stir
        cover pot
        balance wooden spoon precariously on pot handle
        wait 10 minutes
        goto first step (or shut off burner when done)

    Do not bump wooden spoon or it will fall.


Here's a link to [a website](http://foo.bar), to a [local
doc](local-doc.html), and to a [section heading in the current
doc](#an-h2-header). Here's a footnote [^1].

[^1]: Footnote text goes here.

Tables can look like this:

|size | material   |   color      |
|---- |:----------:|  -----------:|
|9    |leather     |  brown       |
|10   |hemp canvas |  natural     |     
|11   |glass       |  transparent |



--------  -----------------------
keyword   text
--------  -----------------------
red       Sunsets, apples, and
          other red or reddish
          things.

green     Leaves, grass, frogs
          and other things it's
          not easy being.
--------  -----------------------

A horizontal rule follows.

***



apples
  : Good for making applesauce.
oranges
  : Citrus!
tomatoes
  : There's no "e" in tomatoe.



| Line one
|   Line too
| Line tree

and images can be specified like so:

![example image](http://placehold.it/800x250 "An exemplary image")


And note that you can backslash-escape any punctuation characters
which you wish to be displayed literally, ex.: \`foo\`, \*bar\*, etc.
