# vigenere-cipher
A Vigenere Cipher implemented in Pharo Smalltalk

## A Note On Version Control
Smalltalk does not play nice with others. 

A quick look inside this repositories `src` directory will show a collection of `*.mcz` files. These are not Smalltalk source files. They are instead Montecellio repositories, Pharo's native version control solution. While Git has been introduced into Pharo 6.0, I am not happy with the implementation. Additionally, I want to keep all my code on GitHub instead of SmalltalkHub. 

Currently I am using Montecellio to commit to a local repository on my computer, then using Git to commit the local repository to GitHub (yes, I'm using version control inside version control). To introduce this repository on your computer you need to do the reverse: use `git clone <repo-url>` as normal, then use Montecellio to introduce the source code into your Smalltalk image.

If anyone has found a better way of doing this, please share.
