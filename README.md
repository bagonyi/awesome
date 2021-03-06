# awesome

List of awesome tools / books / pages that I find useful for (self) development.

## Tools

### Command line

#### [zsh](http://www.zsh.org)

The Z shell (zsh) is a Unix shell that can be used as an interactive login shell and as a powerful command interpreter for shell scripting. Zsh can be thought of as an extended Bourne shell with a large number of improvements, including some features of bash, ksh, and tcsh.

##### [zplug](https://github.com/zplug/zplug)

A next-generation plugin manager for zsh.

#### [tmux](http://tmux.github.io)

tmux is a terminal multiplexer.

What is a terminal multiplexer? It lets you switch easily between several programs in one terminal, detach them (they keep running in the background) and reattach them to a different terminal. And do a lot more.

##### [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

Installs and loads TMUX plugins.

##### [tmux plugins](https://github.com/tmux-plugins)

List of tmux plugins that can be easily installed with Tmux Plugin Manager.

##### [pet](https://github.com/knqyf263/pet)

Simple command-line snippet manager, written in Go.

#### [PsySH](http://psysh.org)

A runtime developer console, interactive debugger and REPL for PHP.

#### [LNAV - The Logfile Navigator](https://github.com/tstack/lnav)

The log file navigator, lnav, is an enhanced log file viewer that takes advantage of any semantic information that can be gleaned from the files being viewed, such as timestamps and log levels. Using this extra semantic information, lnav can do things like interleaving messages from different files, generate histograms of messages over time, and providing hotkeys for navigating through the file. It is hoped that these features will allow the user to quickly and efficiently zero in on problems.

#### [ripgrep](https://github.com/BurntSushi/ripgrep)

ripgrep recursively searches directories for a regex pattern.

#### [fzf](https://github.com/junegunn/fzf)

fzf is a general-purpose command-line fuzzy finder.

#### [fasd](https://github.com/clvv/fasd)

Fasd (pronounced similar to "fast") is a command-line productivity booster. Fasd offers quick access to files and directories for POSIX shells. It is inspired by tools like autojump, z and v. Fasd keeps track of files and directories you have accessed, so that you can quickly reference them in the command line.

#### [sshrc](https://github.com/Russell91/sshrc)

Bring your .bashrc, .vimrc, etc. with you when you ssh. sshrc works just like ssh, but it also sources the ~/.sshrc on your local computer after logging in remotely.

#### [Docker](https://www.docker.com)

Docker is an open platform for developers and sysadmins to build, ship, and run distributed applications, whether on laptops, data center VMs, or the cloud.

#### [Vagrant](https://www.vagrantup.com)

Create and configure lightweight, reproducible, and portable development environments.

##### [Vagrant Manager for OS X](http://vagrantmanager.com)

Manage your vagrant machines in one place with Vagrant Manager for OS X.

#### [Ansible](http://www.ansible.com)

Ansible is a radically simple IT automation platform that makes your applications and systems easier to deploy. Avoid writing scripts or custom code to deploy and update your applications— automate in a language that approaches plain English, using SSH, with no agents to install on remote systems.

#### [Unison](http://www.cis.upenn.edu/~bcpierce/unison) with [onchange.sh](https://gist.github.com/senko/1154509) for keeping local and a remote in sync (bidirectional!)

Unison is a file-synchronization tool for OSX, Unix, and Windows. It allows two replicas of a collection of files and directories to be stored on different hosts (or different disks on the same host), modified separately, and then brought up to date by propagating the changes in each replica to the other.

Note: Unison needs to be installed both locally and on the remote machine (must be same version!).

`onchange` is needed because Unison syncs only if it is asked to do so, it cannot watch directories for changes.

`onchange` is GNU/Linux only, for a cross platform solution look at http://pythonhosted.org/watchdog/ or https://facebook.github.io/watchman/

Usage (assuming `onchange` is on your `$PATH` and ideally using key authentication for SSH):
```bash
cd /path/to/code/locally
onchange unison . ssh://root@virtualmachine//path/to/code/on/remote -batch -contactquietly
```

#### [httpie](https://github.com/jakubroztocil/httpie)

CLI HTTP client; user-friendly cURL replacement featuring intuitive UI, JSON support, syntax highlighting, wget-like downloads, extensions, etc.

#### [git-ftp](https://github.com/git-ftp/git-ftp)

Git powered FTP client written as shell script.

#### [tldr](https://github.com/tldr-pages/tldr)

Simplified and community-driven man pages.

#### [The Pyed Piper](https://code.google.com/p/pyp)

Pyp is a linux command line text manipulation tool similar to awk or sed, but which uses standard python string and list methods as well as custom functions evolved to generate fast results in an intense production environment.

#### [jq](http://stedolan.github.io/jq)

jq is like sed for JSON data – you can use it to slice and filter and map and transform structured data with the same ease that sed, awk, grep and friends let you play with text.

#### [PathPicker](https://github.com/facebook/pathpicker)

PathPicker accepts a wide range of input -- output from git commands, grep results, searches -- pretty much anything. After parsing the input, PathPicker presents you with a nice UI to select which files you're interested in. After that you can open them in your favorite editor or execute arbitrary commands.

#### [ngrok](https://ngrok.com)

ngrok is a reverse proxy that creates a secure tunnel from a public endpoint to a locally running web service. ngrok captures and analyzes all traffic over the tunnel for later inspection and replay.

#### [mitmproxy](https://mitmproxy.org)

An interactive console program that allows traffic flows to be intercepted, inspected, modified and replayed.

#### [Java REPL](https://github.com/albertlatacz/java-repl)

Java REPL is a simple Read-Eval-Print-Loop for Java language.

#### [gnomon](https://github.com/paypal/gnomon)

Utility to annotate console logging statements with timestamps and find slow processes.

#### [pv](http://www.ivarch.com/programs/pv.shtml)

pv - Pipe Viewer - is a terminal-based tool for monitoring the progress of data through a pipeline. It can be inserted into any normal pipeline between two processes to give a visual indication of how quickly data is passing through, how long it has taken, how near to completion it is, and an estimate of how long it will be until completion.

#### [vim](http://www.vim.org)

Vim is an advanced text editor that seeks to provide the power of the de-facto Unix editor 'Vi', with a more complete feature set.

##### [Vundle](https://github.com/gmarik/Vundle.vim)

Vundle, the plug-in manager for Vim.

##### [vim-airline](https://github.com/bling/vim-airline)

Lean & mean status/tabline for vim that's light as air.

##### [fugitive.vim](https://github.com/tpope/vim-fugitive)

fugitive.vim: a Git wrapper so awesome, it should be illegal.

##### [ctrlp.vim](http://kien.github.io/ctrlp.vim)

Full path fuzzy file, buffer, mru, tag, ... finder for Vim.

##### [vim-gitgutter](https://github.com/airblade/vim-gitgutter)

A Vim plugin which shows a git diff in the gutter (sign column) and stages/reverts hunks.

### Linux specific apps

#### [Gnome SSH Tunnel Manager](http://sourceforge.net/projects/gstm)

gSTM is a front-end for managing SSH-tunneled port redirects. It stores tunnel configurations in a simple XML format. The tunnels (local, remote and dynamic) can be managed and individually started/stopped through one simple interface.

#### [easystroke](http://sourceforge.net/projects/easystroke)

easystroke is a gesture-recognition application for X11. It aims to be highly configurable while at the same time providing an intuitive user interface. It was designed primarily for use on a Tablet PC, but it also works well with a mouse.

### macOS specific apps

#### [f.lux (for OS X)](https://justgetflux.com/) or [Redshift (for GNU/Linux)](http://jonls.dk/redshift/)

Both application adjusts the color temperature of your screen according to your surroundings. This may help your eyes hurt less if you are working in front of the screen at night.

#### [Day-O (OS X)](http://shauninman.com/archive/2011/10/20/day_o_mac_menu_bar_clock)

Day-O is a simple menu bar clock replacement with a simple calendar for your Mac.

### OS independent apps

#### [Anki](http://ankisrs.net)

Anki is a program which makes remembering things easy. Because it's a lot more efficient than traditional study methods, you can either greatly decrease your time spent studying, or greatly increase the amount you learn.

#### [MailCatcher](http://mailcatcher.me)

MailCatcher runs a super simple SMTP server which catches any message sent to it to display in a web interface. Run mailcatcher, set your favourite app to deliver to smtp://127.0.0.1:1025 instead of your default SMTP server, then check out http://127.0.0.1:1080 to see the mail that's arrived so far.

#### [PhpStorm](https://www.jetbrains.com/phpstorm)

PhpStorm's smart code editor provides excellent support for PHP (including the latest language versions and frameworks), HTML, JavaScript, CSS, Sass, Less, CoffeeScript, and many other languages. Enjoy coding with intelligent context-aware code completion, error detection, and on-the-fly code inspections & fixes.

#### [Midnight Commander](https://www.midnight-commander.org)

GNU Midnight Commander is a visual file manager. It's a feature rich full-screen text mode application that allows you to copy, move and delete files and whole directory trees, search for files and run commands in the subshell. Internal viewer and editor are included.

#### [muCommander](http://www.mucommander.com)

muCommander is a lightweight, cross-platform file manager with a dual-pane interface. It runs on any operating system with Java support (Mac OS X, Windows, Linux, *BSD, Solaris...).

#### [ScreenCloud](https://screencloud.net)

ScreenCloud makes screenshot sharing easy!

#### [OWASP ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)

The OWASP Zed Attack Proxy (ZAP) is an easy to use integrated penetration testing tool for finding vulnerabilities in web applications.

(I found this as a free alternative to Charles for using it as a web proxy)

#### [SikuliX](http://sikulix.com)

Automate what you see on a computer monitor.

#### Chrome Apps / Extensions

##### [Aliaser](https://chrome.google.com/webstore/detail/aliaser/oflebjnamhkcfcmlgncneemhbijddaae)

Aliaser is a Chrome extension that provides multiple-parameter URL aliasing.

##### [Anki Adder](https://chrome.google.com/webstore/detail/anki-adder/nfpaeklmpflephgpofglphmgbfkkdmmo)

Add cards to Anki directly from Chrome. Perfect for when you quickly want to add something without having to start the desktop version.

##### [Appspector](https://chrome.google.com/webstore/detail/appspector/homgcnaoacgigpkkljjjekpignblkeae)

Detect web applications and javascript libraries run on browsing website.

##### [Cache Killer](https://chrome.google.com/webstore/detail/cache-killer/jpfbieopdmepaolggioebjmedmclkbap)

Automatically clear your browser cache before loading a page. Can be enabled/disabled with a single mouse click.

##### [Chrome Connectivity Diagnostics](https://chrome.google.com/webstore/detail/chrome-connectivity-diagn/eemlkeanncmjljgehlbplemhmdmalhdc)

Chrome Connectivity Diagnostics is a fast and simple network testing and troubleshooting tool for Chrome and Chrome OS. 

##### [CSS Reloader](https://chrome.google.com/webstore/detail/css-reloader/dnfpcpfijpdhabaoieccoclghgplmpbd)

CSS Reloader is a browser extension, that allows you to reload CSS without reloading the page itself.

##### [DomFlags](https://chrome.google.com/webstore/detail/domflags/nindoglnpjcjoaheijieagogboabafkc)

Create keyboard shortcuts to DOM elements for a faster devtools workflow.

##### [DOMListener](https://chrome.google.com/webstore/detail/domlistener/jlfdgnlpibogjanomigieemaembjeolj)

DOMListener is a simple tool that provides convenient interface for observing DOM changes (node removal and addition, attribute and text modifications). Events can be filtered with ease, affected nodes can be highlighted with a single click.

##### [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg)

EditThisCookie is a cookie manager. You can add, delete, edit, search, protect and block cookies!

##### [Google Analytics Opt-out Add-on (by Google)](https://chrome.google.com/webstore/detail/google-analytics-opt-out/fllaojicojecljbmefodhfapmkghcbnh)

Tells the Google Analytics JavaScript not to send information to Google Analytics.

##### [Google Quick Scroll](https://chrome.google.com/webstore/detail/google-quick-scroll/okanipcmceoeemlbjnmnbdibhgpbllgc)

Quick Scroll lets you jump directly to the relevant bits of a Google search result.

##### [jQuery Audit](https://chrome.google.com/webstore/detail/jquery-audit/dhhnpbajdcgdmbbcoakfhmfgmemlncjg)

jQuery Audit creates a sidebar in the Elements panel containing jQuery delegated events, internal data, and more, as live DOM nodes, functions, and objects.

##### [Pesticide](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh)

Faster CSS layout debugging.

##### [Toggle Switch Recent Last Tabs](https://chrome.google.com/webstore/detail/toggle-switch-recent-last/odhjcgnlbagjllfbilicalpigimhdcll)

Toggle between your current and last used (focused) tab with a keyboard shortcut (ALT+Q by default) or mouse click on the icon.

##### [Vimimum](https://chrome.google.com/webstore/detail/vimium/dbepggeogbaibhgnhhndojpepiihcmeb)

The Hacker's Browser. Vimium provides keyboard shortcuts for navigation and control in the spirit of Vim.

##### [Visual Event](https://chrome.google.com/webstore/detail/visual-event/pbmmieigblcbldgdokdjpioljjninaim)

Know what event is bound on each dom element.

## Libraries

#### [NProgress.js](http://ricostacruz.com/nprogress)

A nanoscopic progress bar. Featuring realistic trickle animations to convince your users that something is happening!

## Pages

#### [PHP: The Right Way](http://www.phptherightway.com)

An easy-to-read, quick reference for PHP best practices, accepted coding standards, and links to authoritative PHP tutorials around the Web.

#### [PHP Annotated Monthly by JetBrains](http://blog.jetbrains.com/phpstorm/category/php-annotated-monthly)

Reader's Digest for PHP developers.

#### [PHP Books](http://php-books.com)

What all the fashionable ElePHPants are reading.

#### [DesignPatternsPHP](https://github.com/domnikl/DesignPatternsPHP)

This is a collection of known design patterns and some sample code how to implement them in PHP. Every pattern has a small list of examples (most of them from Zend Framework, Symfony2 or Doctrine2).

#### [Playbook by thoughtbot](https://playbook.thoughtbot.com)

A guide to software development by a software consulting company called thoughtbot.

#### [The Twelve-Factor App](http://12factor.net)

A methodology for building modern, scalable, maintainable software-as-a-service apps.

#### [Learn Git Branching](http://pcottle.github.io/learnGitBranching)

Learn Git Branching is the most visual and interactive way to learn Git on the web; you'll be challenged with exciting levels, given step-by-step demonstrations of powerful features, and maybe even have a bit of fun along the way.

#### [PHP7 tutorial](http://php7-tutorial.com)

The purpose of this site is to help you discover all the changes and new features in PHP7. This tutorial takes the form of simple exercise where you will be asked to solve or fix a bug. Each step corresponds to a RFC and is accompanied by a short explanation.

#### [CheckiO](https://www.checkio.org)

CheckiO is the game for coders. Improve your code with the help of our community. Create missions and challenge your peers.

#### [freeCodeCamp](http://www.freecodecamp.com)

Free Code Camp is an open-source community of busy people who learn to code and build projects for nonprofits.

#### [JSON API](http://jsonapi.org)

A specification for building apis in JSON.

#### [3v4l.org](https://3v4l.org)

Execute your php code; get performance statistics and compare output from all versions.

#### [SQL Style Guide](http://www.sqlstyle.guide)

A consistent code style guide for SQL to ensure legible and maintainable projects.

#### [NodeSchool](http://nodeschool.io)

Choose-your-own-adventure style lessons and learn how to use node.js, npm and other related tools by writing code to solve realistic problems.

#### [The Bash Academy](http://www.bash.academy)

The Bash Academy is an initiative to promote and educate the bash shell language.

## Books

#### [Clean Code: A Handbook of Agile Software Craftsmanship (Robert C. Martin)](http://www.amazon.co.uk/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)

#### [The Clean Coder: A Code of Conduct for Professional Programmers (Robert C. Martin)](http://www.amazon.co.uk/Clean-Coder-Conduct-Professional-Programmers/dp/0137081073)

#### [Patterns of Enterprise Application Architecture (Martin Fowler)](http://www.amazon.co.uk/Enterprise-Application-Architecture-Addison-Wesley-Signature/dp/0321127420)

#### [Mastering Regular Expressions (Jeffrey Friedl)](http://regex.info/book.html)

#### [Specification By Example (Gojko Adzic)](http://specificationbyexample.com)

#### [Professional Software Development (Mike G. Miller)](http://mixmastamyk.bitbucket.org/pro_soft_dev/index.html)

## Newsletters

#### [Servers for Hackers](https://serversforhackers.com)

A newsletter about servers, for programmers.

#### [A Drip of JavaScript](http://adripofjavascript.com)

One quick JavaScript tip, delivered to your inbox every other week.

#### [PHP Weekly](http://www.phpweekly.com)

A free once-a-week newsletter, featuring some great articles, news and blog posts. All About PHP!

#### [Hacker Newsletter](http://www.hackernewsletter.com)

A weekly newsletter of the best articles on startups, technology, programming, and more. All links are curated by hand from the popular Hacker News site.

#### [Dev Tips](https://umaar.com/dev-tips)

Sign up to receive a developer tip, in the form of a gif, in your inbox each week.

#### [JetBrains Newsletters](https://www.jetbrains.com/community/newsletters/)

#### [Understand Legacy Code](https://understandlegacycode.com)

Change messy software without breaking it.

## Music

#### [HARD with STYLE](https://soundcloud.com/hardwithstyle)

A home to lovers of the harder styles in dance music, and a platform for new talents to shine. Based on the ever so popular monthly Podcast, HARD with STYLE has become more than a record label – a movement in its own right.

#### [Brain.fm](https://brain.fm)

While other music is primarily made to sound good and evoke feelings, Brain.fm works with teams of scientists and composers to engineer music specifically designed to help you achieve and sustain deep focus.
