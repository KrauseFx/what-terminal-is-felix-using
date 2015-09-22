# What terminal is Felix using

<img src="Screenshot.png" width="500">

Since I get asked this *every time* I tweet a picture of one of my tools, here's some information about how I set up my terminal:

- I use [iTerm2](https://www.iterm2.com/) instead of the Stock terminal Mac app
- I use [oh-my-zshell](https://github.com/robbyrussell/oh-my-zsh)
- I use [rbenv](https://github.com/sstephenson/rbenv) and [rvm](https://rvm.io/) (on different computers - please only install one of them)
- I use [powerline-shell](https://github.com/milkbikis/powerline-shell) to get those cool path bars. I usually hide the host name and the user, as I usually know who I am
- I use [z](https://github.com/rupa/z) an amazing tool to quickly jump between projects. Like [Alfred](https://www.alfredapp.com/) but for your Terminal reduced to folder search only
- I use the `subl .` command a lot to quickly open a specific folder in Sublime Text. This is what I use to edit my `fastlane` configuration

Add the `subl` command:

```
ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" ~/bin/subl
```
