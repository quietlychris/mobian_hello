### Basic "Hello, world!" Application for Mobian

First we're going to need to have libnotify-bin installed:
```
$ sudo apt-get install libnotify-bin
```

Then put the `hello` file into the Desktop directory, and alter the permission via 
```
$ chmod a+x hello 
```

Then, place the `hello.desktop` file into the `~/.local/share/applications/` directory. 

This should create an icon on the main menu that will create a new notification that says hello for about 3 seconds. 

More options for Icon specs can be found at https://developer.gnome.org/icon-naming-spec/

