#Dotfiles by Phippen

My dotfiles finally got complex enough that they need an install guide.

1. run `rake install` this will link the files to the right places
2. open vim and run `:BundleInstall` this will install vim plugins
3. install the `expect` package. (brew install expect, or your linux equivalent)
4. CONFIGURE YOUR TERMINAL FOR SOLARIZED COLORS OR NOTHING WILL WORK.

##Recent changes

* No more macvim 2014-06-13
* RSpec now runs in terminal and captures output to buffer 2014-06-13
* Many simplifications to setup 2014-06-13
* ls on cd and ctrl-l (screen clear) only, no manual ls 2014-06-13
