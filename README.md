# EverMonkey

[![Build Status](https://travis-ci.org/michalyao/evermonkey.svg?branch=master)](https://travis-ci.org/michalyao/evermonkey)

Evernoting in vscode.

## Features

You can use `ever new` to create an untitle file with metadata support, edit it and use `ever publish` to publish it to evernote. And of course more than that.

Why EverMonkey is better? EverMonkey is Inspired by the Sublime Test one, make local caches to avoid making net request everytime and in result
you got a fast experience. 

Although nowadays it looks simple or maybe ugly, but I am going to make it better. 


**For tags use: you may have to use comma "," to split tags**. This is pretty simple but can be useful, going to be better.  


```
---
title: note title
tags: tag1, tag2, tag3
notebook: notebook
---
```

Commands:
* `ever open` -- open note much like a tree structure. 
* `ever publish` -- update or create a new note. (use this whenver you want to publish your note to Evernote.)
* `ever sync` -- sync account (**Maybe you use evernote concurrently in multi endpoints, most of time I wish you dont do this**)
* `ever new` -- create a new file with markdown language and metadata init.
* `ever token` -- Open dev page to help you configure.

![open-notebook](assets/opennotebooks.png)
![open-note](assets/opennote.png)
![update-note](assets/updatenote.png)
![create-note](assets/createnote.png)


## Extension Settings

**IMPORTANT: Please read this carefully before you start using the extension**

Use command `ever token` to help you get your token & noteStoreUrl. After enter that command (Or your can visit the page directly - [China](https://app.yinxiang.com/api/DeveloperToken.action) | [Other Countries](https://www.evernote.com/api/DeveloperToken.action)).

Then open your user setting by `Preferences: Open User Settings`, and copy&paste token info to (Search `evermonkey` to get you there):

* `evermonkey.token`: your developer token
* `evermonkey.noteStoreUrl`: your API url

**If you get an Unexpected error, then you may have to check the configuration and restart the vscode.**

## Known Issues

- Open note in notebook may cause a mess, because unsupported transfer from enml to markdown.
- You can report issues here [Github issues](https://github.com/michalyao/evermonkey/issues)

TODOs:
+ More markdown style support. 
+ Much better experience.


-----------------------------------------------------------------------------------------------------------

**Have fun!**

