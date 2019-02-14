# my very first webpage

Welcome! 


Some examples of markdown

**Bold Text** done with double asterisks before and after 
or can be done __with double underscore__ before and after 

Is this confusing? Somewhat overlaps with Python's "magic methods" 

On the other hand, *italics* are done with single stars before and after...

Speaking of Python, this is actualy very useful to know this stuff for Jupyter notebooks! 

Hmm, that last line was a little bit messy, I need to make sure I wrap words.  
To do this, use a double space followed by a carriage return. This is all   
according to: https://stackoverflow.com/questions/36728953/how-can-i-wrap-a-line-at-80-characters-in-markdown

Blockquotes are created with a right-facing carrot ( like ^ but turned 90 degrees)  
to the right. 

> I am a mighty blockquote! 

This can span over paragraphs: 

> This blockquote
> 
> just keeps going! 

Note that blockquotes can be nested too! 

> Christian said: 
>> "I am the man!" 

To make a list, just use a dash followed by a space : 

-don't forget: 
- to put a space afterwards
- to make a nice formatted list 

Interestingly, ordered lists don't requrie numbers

so I can just use the same number again and again for a list, or even just  
random numbers! 

Ranking of weird stuff in markdown: 
4. Headings
4. Blockquotes
4. Dashes
4. Ordered lists

NOte you can indent

1. First thing to know
2. About lists is you can use any numbers
    1. And to indent, jsut hit tab and a numbber
2. Then go back to master list i fyou want

**note some text editors will auto-format for you which screws up markdown, if  
you're trying to be purposeful about it**

Unordered lists can also use asterisks, pluses, dashes: 

* Here's an undordered list
* Made using asterisks!

Another useful tool, if you want a paragraph in the middle of a list  
just indent that paragraph 4 spaces or one tab (memories of "Silicon Valley")

1. Here's a list
2. With multiple entries
    I want to mention something here in a paragraph 
3. Then back to the list 

The above did not work. 

Note that code blocks are indented four spaces or a tab. So for example: 

    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/christianzeigler/my-first-website.git
    git push -u origin master

This is good to know, so I can actually show things!  
To add an image, start with exclamation point, brackets for descriptor, then  
parentheses with the href -- no HREF needed! 

    ![descriptor](/absolute/directory/listing/image_file.png)

Inline, you can do "code" or basically format as a "courier" like font using  
tick marks, i.e. `I'd like this to be code`

Can use double tick marks which makes it easier to escape code. 

Now I'm going to create some horizontal rules

Using asterisks: 

***

Using underscores: 

____

Using Dashes: 

----

Note, they are identical ! 

Links are made using just a url e.g. http://www.google.com

but it can be formatted nicely, i.e. [Google Home Page](http://www.google.com)
This is done using brackets around the name you want displayed, followed  
immediately by the link in parentheses

You can also creat a hover for it, by enclosing the hover words in double quotes 
inside the parentheses: 

[Google Search Page](http://www.google.com, "Bing is just some guy in a room Googling as best he can.")

Emails, like linkscan be done directly: 

someemail@emailsystem.com

Or by putting into brackets

<someemail@emailsystem.com> 

Note that bold/italics rules can apply for links, just put all of the brackets, 
parenthesese, etc. inside the asterisks 

I can make references. For example, I found this information all in the markdown  
guide at markdownguide.org [markdown-guide][1]

[markdown-guide]:https://www.markdownguide.org/basic-syntax/


Maybe it would have been useful early on, but some escape characters are useful

this is done with a backslash, so if I wanted to show an asterisk, I put a backslash
in front of it: \* <-- You can't see the backslash though! 

