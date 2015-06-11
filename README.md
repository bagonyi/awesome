# awesome

List of awesome tools / books / pages that I find useful for (self) development.

## Tools

#### [zsh](http://www.zsh.org)

The Z shell (zsh) is a Unix shell that can be used as an interactive login shell and as a powerful command interpreter for shell scripting. Zsh can be thought of as an extended Bourne shell with a large number of improvements, including some features of bash, ksh, and tcsh.

##### [Antigen](https://github.com/zsh-users/antigen)

Antigen is a small set of functions that help you easily manage your shell (zsh) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to zsh, what Vundle is to vim.

#### [tmux](http://tmux.github.io)

tmux is a terminal multiplexer.

What is a terminal multiplexer? It lets you switch easily between several programs in one terminal, detach them (they keep running in the background) and reattach them to a different terminal. And do a lot more.

#### [vim](http://www.vim.org)

Vim is an advanced text editor that seeks to provide the power of the de-facto Unix editor 'Vi', with a more complete feature set.

##### [Vundle](https://github.com/gmarik/Vundle.vim)

Vundle, the plug-in manager for Vim.

##### [vim-airline](https://github.com/bling/vim-airline)

Lean & mean status/tabline for vim that's light as air.

##### [fugitive.vim](https://github.com/tpope/vim-fugitive)

fugitive.vim: a Git wrapper so awesome, it should be illegal

##### [ctrlp.vim](http://kien.github.io/ctrlp.vim)

Full path fuzzy file, buffer, mru, tag, ... finder for Vim.

##### [vim-gitgutter](https://github.com/airblade/vim-gitgutter)

A Vim plugin which shows a git diff in the gutter (sign column) and stages/reverts hunks.

#### [Vagrant](https://www.vagrantup.com)

Create and configure lightweight, reproducible, and portable development environments.

##### [Vagrant Manager for OS X](http://vagrantmanager.com)

Manage your vagrant machines in one place with Vagrant Manager for OS X.

#### [Ansible](http://www.ansible.com)

Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy. Avoid writing scripts or custom code to deploy and update your applications— automate in a language that approaches plain English, using SSH, with no agents to install on remote systems.

#### [PsySH](http://psysh.org)

A runtime developer console, interactive debugger and REPL for PHP.

#### [LNAV - The Logfile Navigator](https://github.com/tstack/lnav)

The log file navigator, lnav, is an enhanced log file viewer that takes advantage of any semantic information that can be gleaned from the files being viewed, such as timestamps and log levels. Using this extra semantic information, lnav can do things like interleaving messages from different files, generate histograms of messages over time, and providing hotkeys for navigating through the file. It is hoped that these features will allow the user to quickly and efficiently zero in on problems.

#### [sshrc](https://github.com/Russell91/sshrc)

Bring your .bashrc, .vimrc, etc. with you when you ssh. sshrc works just like ssh, but it also sources the ~/.sshrc on your local computer after logging in remotely.

#### [Unison](http://www.cis.upenn.edu/~bcpierce/unison) with [onchange.sh](https://gist.github.com/senko/1154509) for keeping local and a remote in sync

Unison is a file-synchronization tool for OSX, Unix, and Windows. It allows two replicas of a collection of files and directories to be stored on different hosts (or different disks on the same host), modified separately, and then brought up to date by propagating the changes in each replica to the other.

Note: Unison needs to be installed both locally and on the remote machine (must be same version!).

Usage (assuming `onchange` is on your `$PATH` and ideally using key authentication for SSH):
```bash
cd /path/to/code/locally
onchange unison . ssh://root@virtualmachine//path/to/code/on/remote -batch -contactquietly
```

#### [MailCatcher](http://mailcatcher.me)

MailCatcher runs a super simple SMTP server which catches any message sent to it to display in a web interface. Run mailcatcher, set your favourite app to deliver to smtp://127.0.0.1:1025 instead of your default SMTP server, then check out http://127.0.0.1:1080 to see the mail that's arrived so far.

#### [httpie](https://github.com/jakubroztocil/httpie)

CLI HTTP client; user-friendly cURL replacement featuring intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, etc.

#### [PhpStorm](https://www.jetbrains.com/phpstorm)

PhpStorm's smart code editor provides excellent support for PHP (including the latest language versions and frameworks), HTML, JavaScript, CSS, Sass, Less, CoffeeScript, and many other languages. Enjoy coding with intelligent context-aware code completion, error detection, and on-the-fly code inspections & fixes.

#### [Gnome SSH Tunnel Manager](http://sourceforge.net/projects/gstm)

gSTM is a front-end for managing SSH-tunneled port redirects. It stores tunnel configurations in a simple XML format. The tunnels (local, remote and dynamic) can be managed and individually started/stopped through one simple interface.

#### [muCommander](http://www.mucommander.com)

muCommander is a lightweight, cross-platform file manager with a dual-pane interface. It runs on any operating system with Java support (Mac OS X, Windows, Linux, *BSD, Solaris...).

#### [easystroke](http://sourceforge.net/projects/easystroke)

easystroke is a gesture-recognition application for X11. It aims to be highly configurable while at the same time providing an intuitive user interface. It was designed primarily for use on a Tablet PC, but it also works well with a mouse.

#### [f.lux (for OS X)](https://justgetflux.com/) or [Redshift (for GNU/Linux)](http://jonls.dk/redshift/)

Both application adjusts the color temperature of your screen according to your surroundings. This may help your eyes hurt less if you are working in front of the screen at night.

#### [ScreenCloud](https://screencloud.net)

ScreenCloud makes screenshot sharing easy!

#### Chrome Extensions

##### [Aliaser](https://chrome.google.com/webstore/detail/aliaser/oflebjnamhkcfcmlgncneemhbijddaae)

Aliaser is a Chrome extension that provides multiple-parameter URL aliasing.

##### [Anki Adder](https://chrome.google.com/webstore/detail/anki-adder/nfpaeklmpflephgpofglphmgbfkkdmmo)

Add cards to Anki directly from Chrome. Perfect for when you quickly want to add something without having to start the desktop version.

##### [Appspector](https://chrome.google.com/webstore/detail/appspector/homgcnaoacgigpkkljjjekpignblkeae)

Detect web applications and javascript libraries run on browsing website.

##### [Cache Killer](https://chrome.google.com/webstore/detail/cache-killer/jpfbieopdmepaolggioebjmedmclkbap)

Automatically clear your browser cache before loading a page. Can be enabled/disabled with a single mouse click.

##### [CSS Reloader](https://chrome.google.com/webstore/detail/css-reloader/dnfpcpfijpdhabaoieccoclghgplmpbd)

CSS Reloader is a browser extension, that allows you to reload CSS without reloading the page itself.

##### [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg)

EditThisCookie is a cookie manager. You can add, delete, edit, search, protect and block cookies!

##### [Google Quick Scroll](https://chrome.google.com/webstore/detail/google-quick-scroll/okanipcmceoeemlbjnmnbdibhgpbllgc)

Quick Scroll lets you jump directly to the relevant bits of a Google search result.

##### [Toggle Switch Recent Last Tabs](https://chrome.google.com/webstore/detail/toggle-switch-recent-last/odhjcgnlbagjllfbilicalpigimhdcll)

Toggle between your current and last used (focused) tab with a keyboard shortcut (ALT+Q by default) or mouse click on the icon.

##### [Vimimum](https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb)

The Hacker's Browser. Vimium provides keyboard shortcuts for navigation and control in the spirit of Vim.

##### [Visual Event](https://chrome.google.com/webstore/detail/visual-event/pbmmieigblcbldgdokdjpioljjninaim)

Know what event is bound on each dom element.

## Pages

#### [PHP Annotated Monthly by JetBrains](http://blog.jetbrains.com/phpstorm/category/php-annotated-monthly)

Reader's Digest for PHP developers.

#### [PHP Books](http://php-books.com)

What all the fashionable ElePHPants are reading.

#### [DesignPatternsPHP](https://github.com/domnikl/DesignPatternsPHP)

This is a collection of known design patterns and some sample code how to implement them in PHP. Every pattern has a small list of examples (most of them from Zend Framework, Symfony2 or Doctrine2).

## Books

#### [Clean Code: A Handbook of Agile Software Craftsmanship (Robert C. Martin)](http://www.amazon.co.uk/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)

#### [The Clean Coder: A Code of Conduct for Professional Programmers (Robert C. Martin)](http://www.amazon.co.uk/Clean-Coder-Conduct-Professional-Programmers/dp/0137081073)

#### [Patterns of Enterprise Application Architecture (Martin Fowler)](http://www.amazon.co.uk/Enterprise-Application-Architecture-Addison-Wesley-Signature/dp/0321127420)

#### [Mastering Regular Expressions (Jeffrey Friedl)](http://regex.info/book.html)

## Misc

#### [Anki](http://ankisrs.net)

Anki is a program which makes remembering things easy. Because it's a lot more efficient than traditional study methods, you can either greatly decrease your time spent studying, or greatly increase the amount you learn.

#### [HARD with STYLE](https://soundcloud.com/hardwithstyle)

A home to lovers of the harder styles in dance music, and a platform for new talents to shine. Based on the ever so popular monthly Podcast, HARD with STYLE has become more than a record label – a movement in its own right.
