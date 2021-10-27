# Writing Notes Using MarkDown

## This is an H2 tag - ## makes it smaller and not a header

## Overview 
* How to install an Editor
* Purpose of MarkDown
* MarkDown Examples; Italicing, Bolding, Listing
* Embedding Code Into MarkDown Notes 


### How to Install an Editor
* To install editor, excecute the command below from the terminal 
* to install the 'visual-studio-code' editor, execute the command below from the terminal 

```
brew install --cask visual-studio-code
```

### MarkDown Examples

#### Italicizing
8 To italicize a phrase , or some text, _wrap_ the text in underscores
_

#### Bolding
* To bold a phrase, or some text, **wrap** the text in double asterisks **. 

#### Listing
* To creat a List, begin each line with a single asterisk *.
* This is another item in the list
* This is the third item in the list
* You can create sublists by appending a tab before an asterisks within a list. 
    * This is a sublist item
    * THis is another sublist item
    * And this is a third sublist item


### Embedding Code Into MarkDown Notes
* To embed code in-line `wrap` a phrase or text, with single backticks `. 
* To embed multiline code, wrap a body of txt in triple backticks,on a new line

```
print ("Hello world!")
```

In the slides, it said hat this is the python equivalent of the java snippet below

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello world!);
    }
}
```

### How to Embed Hyperlinks into MarkDown Notes
* To embed a link in MarkDown, wrap the phrase you would like become a link in square brackets []. 
    *Follow the square brackets with a wrapping of the link in parenthesis. 
* [Here](https://school.zipcode.rocks/calendar) is an example of a link to your student portal! 


### How to `push` notes to `GitHub`
1. To create a new repository in github, navigate to [Https://github.com/new]
2. Select the organization / accound that we would like add the repository to 
3. Click create repository
4. Enter the name ofo the repositor
5. Copy the line affixed with `git remote add orgin`
6. Navigate to the directory containing the notes is `my-notes` )
7. Excute the command below to initialize this directory as a local `git` repository
    * `git init`
8. Execute the command below to index all files
    * `git add.`
9. Execute the command below to add all indexed files to staging
    *`git commit -m "I just made my first commit"`
10. Execute the command below to `push` all staged files to the remote repository
