# comments package

A multi language line commenter that is designed to ease the problems of code writing.  The project now in its infancy is simply a universal code snippet platform that allows you to make comments easily when switching between programming languages.  Using the corresponding comment commands will create a comment the same whether you are in c, css, html or javascript.

![A screenshot of your package](https://f.cloud.github.com/assets/69169/2290250/c35d867a-a017-11e3-86be-cd7c5bf3ff9b.gif)

## Usage
##### Comment Code (cc)
Basic 1 line comment

##### Comment Code Line(ccl)
This is the same as the above command, its there in case some other mod already bound cc as a snippet.

##### Comment Code TODO(cct)
1 Line Comment with TODO: and places your cursor after

##### Comment Code REVIE(ccr)
1 Line Comment with REVIEW: and places your cursor after

##### Comment Code FIXME(ccf)
1 Line Comment with FIXME: and places your cursor after

##### Comment Code XXX(ccx)
1 Line Comment with XXX: To signify mysteriously working code, that may need some improvement.

##### Comment Code Block Doc(ccbd)
Multi line comment: Puts cursor at title, tab to get to description after entering title

##### Comment Code Block Function(ccbf)
Multi line comment: Puts cursor at title, tab to get to description after entering title

## Something is not correct for your language?
Sorry, I don't write code in every language, but I have google.  Fix it and send me a pull request.

## TODO In Future?
* Multiple sizes for comment blocks(ie ccdb5 for 5 lines of docblock comment)
* Create auto blocks of comments when code reaches a certain size
* Customizable blocks of comments(ie more #'s, /'s, ;'s or whatever your language uses for comments')
* Auto doc comment blocks on new file
* Auto doc comment blocks on new function or object(at a certain size option)
* Time stamps and git email(author) added to comment doc and function blocks
* Maybe some way to force people to make comments before continuing to code in their file?

## Some Good Reading on writing better code
[Code Comment Tips ](http://blog.ram.rachum.com/post/103051530508/code-comments-that-i-find-helpful)

[Tips To Code Better](http://www.craigsefton.com/programming/tips-better-code-comments/)

## Wanna help?
Cool, send your pull request.  This is my first atom package so development will be a bit slow.
