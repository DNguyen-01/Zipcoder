# GitHub Intro

* Git - used to communicate with version control systems


* Branch - allows you to make multiple version of the project to edit/de-bug w/o messing up the master

**BestPractices**

* commit - early and often
* comment - always messages with a short, meaningful comments
* Review code before pushing it 
* Maintain a proper - .gitignore
* Run all tests, make sure code compiles before committing / pushing changes
	* **_IDE_** - look up term

**Don't**
* do not work on the Main
* Delete un-merged branches
* Commit code that does not compile, or fails unit tests

* Work Flow - Take down Changes 
	* Commit
		* creates a log (specific hash) of the code you're working on 
		* Don't have to push code until its working 
	* Pull
		* fetch + pull
	* Merge
		* pull down changes to master from remote to local, then merge them into your branch    