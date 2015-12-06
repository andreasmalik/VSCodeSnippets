# VSCodeSnippets

Useful JavaScript-Snippets for Visual Studio Code. I was inspired by the Extension "JavaScript (ES6) code snippets" 
by "charalampos karypidis". You can download the original extension at the marketplace at 
https://marketplace.visualstudio.com/items/xabikos.JavaScriptSnippets. 

I added some additional snippets for my personal tasks and styles. Hopefully you like it!


## Snippets

* Import
* Export 
* Classes / Methods / Properties
* Loops
* Functions
* Console
* Misc


## Mac OS X Installation

You have several possible methods to install the snippets. Select your favorite one. 
After changing the snippets you have to restart VSCode! Please read the VSCode-documentation
for other operating systems and installation methods.

### Copy file

Open the Terminal and download the project with

```
$ git clone https://github.com/andreasmalik/VSCodeSnippets.git

$ cd VSCodeSnippets/
```

Copy the javascript.json file to the VSCode snippet path

```
$ cp javascript.json ~/Library/Application Support/Code/User/snippets/
```

Restart VSCode.

### Copy Content 

Open VSCode and select "Code" -> "Preferences" -> "User Snippets" and paste the content of the javascript.json file in it.

Restart VSCode.


## Todo

I will extend the snippets for some features:

* JSDoc-Comments