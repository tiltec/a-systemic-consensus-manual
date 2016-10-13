# Collaborate

This book is intended to be a resource for making group decisions specifically and collaboration generally which is free, open-source, living, pluralistic, utilitarian, beautiful and fun.

* **Free.** Free access financially (e.g. no cost), energetically (e.g. no 'sign-up-to-get-access'), etc, etc. Also free of external dependencies.
* **Open-source.** Following on from free, the source is open - not just the end product.
* **Living.** Alive in and of itself. Essentially meaning that it's not tied to any one author (mortal), but a changing collective. 
* **Pluralistic.** Accommodating a variety of viewpoints without moralizing, rejecting the very concept of The Singular And Exclusive True Way™ 
* **Utilitarian.** Vaguely, bringing use to as many as possible. Perspectives, accessibility, languages, etc. Note: _not_ majoritarian.
* **Beautiful.** To balance utilitarianism (and bring in endless design discussions, ha!)
* **Fun.** Because what is the point otherwise? 

## Ways to contribute

* Get talking! [@DougInAMug](https://twitter.com/DougInAMug)
* Send suggestions, ideas or interesting material.
* Make in-line comments. (Make an account on [Gitbook.com](https://www.gitbook.com/join))
* Send text, graphics or whole articles by email.
* Clone, edit, push to fork and make pull requests...

## Set-up

This book uses all free and open source applications and services: gitbook, gitbook.io, gitbook.com, github.com and git - thanks you gitty people. Some images produced thanks to Inkscape, hand drawn ones thanks to Xournal.

The master branch is hosted on both gitbook.com (from which it is built and published) and github.com (where the source can be forked, merged, etc). These repositories automatically synchronize when a change is made to the other thanks to some cool webhook stuff. So pushing looks like this:


```
																 -- Doug local repo
																|-- Mandy local repo
Published output <-- gitbook.com repo <--> github.com repo <----- h4ktehpl4net local repo
															    |-- DeepBlue local repo
																 -- (You?) local repo
```																
																																							
## Direct contribution

```bash
# 1 clone
$ git clone https://github.com/DougInAMug/a-systemic-consensus-manual.git
$ cd a-systemic-consensus-manual 

# 2 change stuff...

# 3 push to your own fork
$ git remote set-url origin https://github.com/yourUserName/yourRepoName.git # change URL to your stuff

# 4 make pull request via github.com 
```

If you want to contribute directly and you're not sure about the technical stuff, you can do it - it's not too hard to learn. Check out [this](https://toolchain.gitbook.com/) guide to gitbook including how to write in Markdown and [this](https://git-scm.com/book/en/v2) guide to git. Make a coffee for your friendly, local nerd and go over it with them.
