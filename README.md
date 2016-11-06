# What terminal is Felix using

<img src="ScreenshotNew.png" width="500">
<img src="Screenshot.png" width="500">

Since I get asked this *every time* I tweet a picture of one of my tools, here's some information about how I set up my terminal:

- I use [iTerm2](https://www.iterm2.com/) instead of the Stock terminal Mac app
- I use [oh-my-zshell](https://github.com/robbyrussell/oh-my-zsh)
- I use [rbenv](https://github.com/rbenv/rbenv) and [rvm](https://rvm.io/) (on different computers - please only install one of them)
- I use [Solarized Dark](http://ethanschoonover.com/solarized) for the terminal colors
- I use [powerline-shell](https://github.com/milkbikis/powerline-shell) to get those cool path bars. I usually hide the host name and the user, as I usually know who I am
- I use the [Meslo Powerline Font](https://github.com/powerline/fonts/blob/master/Meslo/Meslo%20LG%20M%20DZ%20Regular%20for%20Powerline.otf) as you need a font that supports the directory characters for `powerline`
- I use [z](https://github.com/rupa/z) an amazing tool to quickly jump between projects. Like [Alfred](https://www.alfredapp.com/) but for your Terminal reduced to folder search only
- I use the `subl .` command a lot to quickly open a specific folder in Sublime Text. This is what I use to edit my `fastlane` configuration

Add the `subl` command:

```
sudo mkdir -p "/usr/local/bin/" && ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl
```

----

Also, check out [KrauseFx/dotfiles](https://github.com/KrauseFx/dotfiles) for the dot files I'm using 🚀

----
