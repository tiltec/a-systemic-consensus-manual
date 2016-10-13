# Collaborate

## Intention 

> A resource for making group decisions specifically and collaboration generally which is free, open-source, living, pluralistic, utilitarian, beautiful and fun.
>
> Doug (2016-10-13)

Breakdown:

* **Free.** Free access financially (e.g. no cost), energetically (e.g. no 'sign-up-to-get-access'), etc, etc. Also free of external dependencies.
* **Open-source.** Following on from free, the source is open - not just the end product.
* **Living.** Alive in and of itself. Essentially meaning that it's not tied to any one author (mortal), but a changing collective. 
* **Pluralistic.** Accommodating a variety of viewpoints without moralizing, rejecting the very concept of The Singular And Exclusive True Way™ 
* **Utilitarian.** Vaguely, bringing use to as many as possible. Perspectives, accessibility, languages, etc. Note: _not_ majoritarian.
* **Beautiful.** To balance utilitarianism ( and bring in endless design discussions ;p )
* **Fun.** Because what is the point otherwise?

## On living resources

Let's look at books. There are shit loads of books, way more than anyone can read:

> As long as the centuries continue to unfold, the number of books will grow continually, and one can predict that a time will come when it will be almost as difficult to learn anything from books as from the direct study of the whole universe. It will be almost as convenient to search for some bit of truth concealed in nature as it will be to find it hidden away in an immense multitude of bound volumes.
>
> — Denis Diderot, "Encyclopédie" (1755)

Typically, a minority of books go big time, everyone get's the view point of one author, the publisher gets rich, the author dies, the book becomes history and everyone is doomed to quote it forever more. What if books had their own life and survived their creator, evolving and adapting to the needs of the time? Let's make this one. 

## How to contribute

* Get talking! @DougInAMug
* Send suggestions, ideas or interesting material. @DougInAMug
* Make in-line comments. (Make an account on [Gitbook.com](https://www.gitbook.com/join))
* Send text, graphics or whole articles by email.
* Make pull requests... keep reading

## Current tech

This book uses several free and open source applications and services: gitbook, gitbook.io, gitbook.com, github.com and git. Thanks you gitty people.

The master branch is hosted on both gitbook.com (from which it is automatically built and published) and github.com (where it can be forked, merged, etc). These repositories automatically synchronize when a change is made to the other thanks to some cool webhook stuff. So pushing looks like this:

```
																 -- Doug local repo
																|-- Mandy local repo
Published resource <-- gitbook.com repo <--> github.com repo <----- h4ktehpl4net local repo
															    |-- DeepBlue local repo
																 -- (You?) local repo
```																
																						
Some images produced thanks to Inkscape, hand drawn ones thanks to Xournal. 						   
																												
## How to contribute directly

Clone the github repo, change stuff, push changes to a fork and make a pull request.

```bash
# 1 clone
$ git clone https://github.com/DougInAMug/a-systemic-consensus-manual.git
$ cd a-systemic-consensus-manual 

# 2 change stuff...

# 3 push to your own fork
$ git remote set-url origin https://github.com/yourUserName/yourRepoName.git # change URL to your stuff

# 4 make pull request via github.com 
```

The official guide to gitbook including writing in Markdown (.md) is found [here](https://toolchain.gitbook.com/). The Pro Git book is available [here](https://git-scm.com/book/en/v2) - but it is highly recommended to grab you're nearest nerd if black-boxes and coding scares you.
