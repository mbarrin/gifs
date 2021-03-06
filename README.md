# Gifs - command line gif storage and upload


Gifs helps you manage your gif collection from your command line. gifs simplifies uploading your gifs and storing their URLs for later use while also copying their URL into your clipboard for easy access.

## How do I use this magic
It's simple really.

```bash
$ gifs
Usage: gifs [caption] [url/path] <- Uploads image and saves as caption
       gifs [caption]            <- Returns the URL for that caption

$ gifs nailed.it ~/Desktop/nailed.it.gif
Saved nailed.it as http://i.imgur.com/llFuLyX.gif
I even copied it to your clipboard

$ gifs nailed.it
Found nailed.it: copied http://i.imgur.com/llFuLyX.gif to your clipboard

$ gifs
nailed.it:      http://i.imgur.com/llFuLyX.gif
```

Or in gif form

![gifs demo](http://i.imgur.com/bLx5KZN.gif)

## Inspiration

gifs is inspired by [@eugeneius](https://github.com/eugeneius)' "genius" (see what I did there?) use of Zach Holman's [boom](https://github.com/holman/boom) gem for managing his most fantastic gif collection. For every emotion, @eugenius has an appropirate gif. This tool is built to give me a competitive advantage such that I can catch up with him
