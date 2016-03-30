# VSCodeSnippets

Useful JavaScript-Snippets for Visual Studio Code. I was inspired by the Extension "JavaScript (ES6) code snippets" 
by "charalampos karypidis". You can download the original extension at the marketplace at 
https://marketplace.visualstudio.com/items/xabikos.JavaScriptSnippets. 

I added some additional snippets for my personal tasks and styles. Hopefully you like it!


## Snippets

### Nodeunit

| Name  							| Prefix / Command	| 
| :------------ 					|:----------------- |
| Nodeunit test case method      	| nutest 			|
| Nodeunit test group     			| nugroup 			|


### JSDoc

| Name  												| Prefix / Command	| 
| :------------ 										|:----------------- |
| JSDoc description block      							| jsddesc 			|
| JSDoc file header block      							| jsdfile 			|
| JSDoc class block for ES6 2015 specification     		| jsdclass 			|
| JSDoc set property block for ES6 2015 specification  	| jsdset 			|
| JSDoc get property block for ES6 2015 specification   | jsdget 			|
| JSDoc method block for ES6 2015 specification   		| jsdmet 			|


### Import

| Name  												                            | Prefix / Command	| 
| :------------ 										                            |:----------------- |
| Imports entire module statement in ES6 syntax			                            | imp 			    |
| Imports only a portion of the module in ES6 syntax	                            | imd 			    |
| Imports everything as alias from the module in ES6 syntax	                        | ime 			    |
| Imports a specific portion of the module by assigning a local alias in ES6 syntax	| ima 			    |
| Export named function in ES6 syntax	                                            | enf 			    |


### Other possible snippets (documentation will follow):

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
$ cp javascript.json ~/Library/Application\ Support/Code/User/snippets/
```

Restart VSCode.

### Copy Content 

Open VSCode and select "Code" -> "Preferences" -> "User Snippets" and paste the content of the javascript.json file in it.

Save the file.


##License

VSCodeSnippets is released under the MIT license. See LICENSE for details.