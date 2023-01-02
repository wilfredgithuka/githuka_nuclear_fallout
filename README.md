## Githuka Nuclear Fallout Dot Files
### A collection of my system's config files incase of a system failure

![fall-out](https://en.wikipedia.org/wiki/Fallout_shelter#/media/File:Fallout_shelter_sign_(US).jpg)

### System Info

* OS: Arch Linux
* Hostname: nzc++[97]
* Kernel Release: 6.0.12-arch1-1
* WM: i3
* RAM: 7828 MB
* Processor Type: Intel(R) Core(TM) i5-4200U CPU @ 1.60GHz

What works on my machine might not neccessarily work on yours, so copy carefully.

### Config Files List

* Vim files (vimrc) and other files.
* i3wm config files.
* Vim+Latex setup
* fcitx5 wps+chinese input files.
* xfce4 apps which I use.

### Vimtex Config Notes

* I use [vim-plug](https://github.com/junegunn/vim-plug) to install my vim plug-ins. I
however prefer a minimalist system so I keep only the most essential themes. 0 bloating.

* [VimTeX](https://github.com/lervag/vimtex#requirements) is a modern Vim 
filetype and syntax plugin for LaTeX files. This tutorial is preety much
what you need to install and get started using Vimtex.

* [Ejmatnast](https://www.ejmastnak.com/tutorials/vim-latex/vimtex/#getting-started) has
written some good notes on getting started with Vim-latex. He comes in highly recommended.

* [Papercolor](https://github.com/NLKNguyen/papercolor-theme) is you need your vim to use the
famous papercolor theme, I suggest this one. Its beautiful and easy on the eyes.

### fcitx5 Config Notes

On Linux, fcitx is my go-to tool for Chinese input. However its a pain to install and after
every system format am normally fingers-crossed on whether it shall work. fcitx5 is the newest
and works on i3. Some config needs to be done to work with WPS Office suite.

* Read carefully on how to [install](https://wiki.archlinux.org/title/Fcitx5) fcitx5.
* I start my wm using the startx command, so the follwing needs to be in my environment variables.

```
GTK_IM_MODULE=fcitx
QT_IM_MODULE=fcitx
XMODIFIERS=@im=fcitx
```

