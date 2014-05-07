Google Closure Compiler Script
==============================

This is a small python script that allows you to call the [Google Closure Compiler API](https://developers.google.com/closure/compiler/) from the command line to minify your files. It is mostly taken from the [example](https://developers.google.com/closure/compiler/docs/api-tutorial1) in the api documentation.

To use the script: 

1. Clone this repo to wherever you want on your computer
2. Make the googcc file executable (chmod a+x googcc)
3. In the terminal, go to /usr/local/bin
4. Type in 'ln -s _path-to-googcc-file_
5. Restart (or just reload) shell session

Then you should be able to call this script like this at the prompt from any directory:
`googcc <original-file-name> <minified-file-name>`

I've been using a full path for both of those files, but I don't think you need to.

Right now it's just set to remove whitespace-only, but obviously you can fork it and have it do whatever you like.

Hopefully this doesn't delete all the files on your computer, but I've got no guarantees for you on that one. There is a high likelihood that it won't work for you since this is the first time I've done anything with python.
