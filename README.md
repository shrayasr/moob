#M O O B

###What is it?
moob is a clone of the [@holman/boom](www.github.com/holman/boom) repo but just done purely with the shell . 

###Why re-invent the wheel , u ass ?
Well mainly because i dont know ruby :P But also because i wanted to see how we could manage such chunks of data through just the shell . 

###Install
`moob init` will initialize a moob repository in your current directory and set the environment variable `$MOOB_PATH` to it. 

###Quickie guide
```
$ moob init
moob! initialized in '/users/shrayas/'

$ moob bookmarks
moob! Created a new list : 'bookmarks'

$ moob bookmarks fb www.facebook.com
moob! 'fb' in 'bookmarks' is www.facebook.com . Gotcha !

$ moob fb
moob! Just copied www.facebook.com to your clipboard
```
    
###Features
I'm too bored to write it in here , just go see [his wiki](https://github.com/holman/boom/wiki/Commands) . All those commands are going to be supported (including the copy to shell , though currently on OSX only)

###Moar
I tried to do this as a 45 minute hackathon but turns out there is more than meets the eye . This needs a whole lot of thinking to build . Hoping it'll be done by this weekend :) Keep an eye out. Cheers !