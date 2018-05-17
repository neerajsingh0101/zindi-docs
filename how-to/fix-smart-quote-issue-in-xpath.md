# How to fix smart quote issue in xpath

xpath will fail if you have selector as shown below.

```
//a[text()[contains(.,“citrix-61538”)]]
```

It's a bit hard to notice but the quotes used here are smartquotes.
They make xpath invalid.

The fix is to switch to regular quotes like this.

```
//a[text()[contains(.,"citrix-61538")]]
```


# Disable smartquotes in mac

To disable smartquotes in Mac 
Open System Preferences > Keyboard > uncheck "Use smart quotes and dashes"
