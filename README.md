#M O O B

###What is it?
moob is a clone of the [@holman/boom](http://www.github.com/holman/boom) repo but just done purely with the shell . 

###Why re-invent the wheel , u ass ?
Well mainly because i dont know ruby :P But also because i wanted to see how we could manage such chunks of data through just the shell . 

###Install
`moob init` will initialize a moob repository in your `home` directory

###Quickie guide
```
$ moob init
moob! initialized

$ moob bookmarks
moob! Created a new list : 'bookmarks'

$ moob bookmarks fb www.facebook.com
moob! 'fb' in 'bookmarks' is www.facebook.com . Gotcha !

$ moob fb
moob! Just copied www.facebook.com to your clipboard
```
    
###Features
I'm too bored to write it in here , just go see [his wiki](https://github.com/holman/boom/wiki/Commands) . All those commands are going to be supported. 

Copy to shell supported out of the box with OXS but needs `xclip` or `xsel` to be installed otherwise