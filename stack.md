####What is CORS?
* Cross-Origin Resource Sharing
* [barryvdh/laravel-cors](https://github.com/barryvdh/laravel-cors)
L:  *Laravel*, *API*

####What is JWT authentication?
* JSON Web Token [tymondesigns/jwt-auth
](https://github.com/tymondesigns/jwt-auth)
* [Token-Based Authentication for AngularJS and Laravel Apps](https://scotch.io/tutorials/token-based-authentication-for-angularjs-and-laravel-apps)
L: *Laravel*, *AngularJS*

####How to use DevTools Timeline?
* The [DevTools Timeline](https://developers.google.com/web/updates/2015/03/devtools-timeline-now-providing-the-full-story) panel has always been the best first stop on the path to performance optimization. 
L: *JS*, *Chrome*, *Tools*

####How to use Sublime Text?
* [Open Sublime Text From cli Using subl.exe (Win)](https://scotch.io/tutorials/open-sublime-text-from-the-command-line-using-subl-exe-windows)
* [Keyboard Shortcuts](https://scotch.io/bar-talk/sublime-text-keyboard-shortcuts)
* package [gitgutter](https://github.com/jisaacks/GitGutter), [material-theme](https://github.com/equinusocio/material-theme), [SidebarEnhancements](https://github.com/titoBouzout/SideBarEnhancements), [AdvancedNewFile](https://github.com/skuroda/Sublime-AdvancedNewFile), [DocBlockr](https://github.com/spadgos/sublime-jsdocs)
* p [sftp](https://wbond.net/sublime_packages/sftp/settings) create/edit the `sftp-config.json` file in project folder, `Diff` this file first!
* vidoe [Sublime Text Mastery](https://laracasts.com/series/sublime-text-mastery)
* tips On UK keyboard `show console`will be `Ctrl+'` ***not*** <code>Ctrl+`</code>

####How to use PHPStorm?
* Hello (Learn every inch of your IDE!)  
* Minimalism (use keyboard command, turn off 1.Status Bar 2.breadcrumb )
* Color IDE (plugin change side bar background-color)
* Two Important Key bindings (1. Navigate/File... 2. Navigate/File structure) `Ctrl+Shift+A` Help/Find Action... `Ctrl+Shift+N` Navigate/Symbol... go to method
* Create New Files Quickly (`Ctrl+Up` find folder, `Ctrl+N` new file)
* Custom File Templates (Q: How to use Code Templates? New template Eloquent Model, class  extends Eloquent)
* Live Templates (`Ctrl+J` 'textfield' bootstrap form-group input text Q: How to add more live template?) (Q: What is Emmet?)
* Custom Formatting (Code Style/PHP Q: follow which code style guide?)
* Refactoring: 
 * Name and Method (`Ctrl+T`Refactor/**extract** method. Refactor/**rename**) (cursor then `Ctrl+C`copy whole line, cursor then `Ctrl+X` delete whole line)
 * Pull Up (Refactor/**Pull Members Up**)
 * Extract Interface (From a class extract interface with same functions)
 * Extract and Inline Variable (From a string extract Variable `Ctrl+Alt+V`, Revise inline Variable )
* Fast Composition ( Code/Generate `Ctrl+I` construct, cursor on parameter `Alt+Enter` initialize fields)
*  Navigating to Sass Symbols (hunting particularly class `Ctrl+Shift+N` Navigate/Symbol...)
* Laravel Facades Issue (package: laravel-ide-helper)
* Multiple Cursors (Find/Select All Occurrences `Ctrl+Alt+Shift+J`, Add Selection for Next Occurrence `Alt+J`)
* Splits (`Ctrl+F12` split vertically, then `Ctrl+Shift+F12`Goto Next Splitter )
* Vi-Mode With Mappings (also support**imap** `.ideavimrc`)
* Xdebug (Setting PHP/Interpreter, Notice check `php --ini`, Also in PHPUnit Xdebug setting on Windows, Set breakpoint, Run/Debug)
* Xdebug and Laravel
* Composer Dependencies and PHPStorm (Tool/Composer)
* Testing in PHPStorm (PHP/PHPUnit/Use Composer autoloader)
* Code Coverage (phpunit.xml [**whitelist**](https://phpunit.de/manual/current/en/code-coverage-analysis.html) It is mandatory to configure a whitelist for telling PHPUnit which sourcecode files to include in the code coverage report. )
* Why I Use Both PHPStorm and Sublime Text
* Automatic PSR-4 Namespacing (Directories/Folders **p** package prefix)

####How to use Vim?
* Finding Your Way Around (MacVim support `Ctrl+S` save) (iterm2 + oh-my-zsh) (~/.vimrc) (win babun cygwin oh-my-zsh) (:colorscheme Tab, :so %) (backspace)
* Mappings and Commands (`nmap ,ev :tabedit $MYVIMRC`) (`:bd` close buffer)
* A Prettier Vim (vim-atom-dark)
* Optimizing Window Splits (`:vsp`)
* Vundle and Better File Browsing (manage plugins [VundleVim](https://github.com/VundleVim/Vundle.Vim),  directory listing `-` [vinegar.vim](https://github.com/tpope/vim-vinegar), sidebar `,1` [NERD Tree](https://github.com/scrooloose/nerdtree))
* Faster Browsing with Ctrl+P (VimScript find file [ctrlp.vim](https://github.com/ctrlpvim/ctrlp.vim),  switch path to file `Ctrl+d`, go-to symbol  `<c-R> :CtrlPBufTag<cr>`,  recent used file `,u` ))
* Configuration Tweaks (go to next tab`gt`)
* Browse Like a Pro With Ctags (database index)(`di'` delete in` '' `, `ci(` change in (), INSERT MODE)(`va'` select all in `''` include `''`, `vi{` select all in `{}` exclude `{}`)(`,f` show first, then `:tn`show next, `:ts` show all selected)(`Ctrl+[` go to tag)(`Ctrl+6carret` go to previous file)(`:bufdo bd` [bufdo runs command for all buffers](http://vim.wikia.com/wiki/Run_a_command_in_multiple_buffers))
* Custom Highlighting (Not work in babun)
* Site-Wide Search and Replace (`:Ag 'search'` [ag.vim](https://github.com/rking/ag.vim)) (cygwin package `the-silver-searcher`use babun/pact) ([greplace.vim](https://github.com/skwp/greplace.vim))(`gg` go to top, `Shift G` go to bottom)
* PeepOpen
* Laravel-Specific Mappings
* Managing Snippets ([snipMate](https://github.com/garbas/vim-snipmate) in snippets folder)(`zc` close, `zo` open, and `za` toggle ***folds***)(ReloadAllSnippets() After create new snippets)
* Surrounding Text([surround](https://github.com/tpope/vim-surround) `cs'<q>` In html `dst` delete surrounding tag)
* PHP Optimizations(--VISUAL-- model select all `:` sort)([vim php namespace](https://github.com/arnaud-lb/vim-php-namespace))
* Auto-Completions (`Ctrl+N` per-match result, then `Ctrl+N` Don't `Enter` already in)(`:ls` list all buffer)(--VISUAL-- `Shift+j` Join Lines)
* Automatic PSR-2 Formatting 
* Marks(`m` + `any` set mark `:marks` ,  `'` go to mark, use Capital)(`yiw`)
* Tabs, Indents, and Spaces (`vat` select all in tag, `dat` delete all in tag, `o` start a new line INSERT, `Shift+o` start a new line above)
* Fun With Macros(`qq` begin macro, `Esc` then `q` stop macro, `@q` recall macro) (`"qp` get register paste) (`yiw` copy word in clip, `p` paste out, In command `Ctrl+r` paste out)
* PHP Documentor and Ultisnips [tobyS/pdv](https://github.com/tobyS/pdv)
 [ultisnips](https://github.com/SirVer/ultisnips)(UltiSnipsEdit)
####How can I see what has changed in a file before committing to git?
* `git diff` or `git diff filename`

####How to be a Junior Developer?
* [10 TIPS FOR NEWBIES/JUNIOR DEVELOPERS](http://goodheads.io/2015/07/09/10-tips-for-newbiesjunior-developers/)
* [The 10 Commandments of a Born again Developer](http://goodheads.io/2015/07/26/the-10-commandments-of-a-born-again-developer/)

####What is Model Relationships?
* [Eloquent: Relationships](https://laravel.com/docs/5.2/eloquent-relationships)
* [7 Laravel Packages to Supercharge your Models](http://goodheads.io/2016/04/17/7-laravel-packages-to-supercharge-your-models/)

####What is Capistrano deployment script?
* [Capistrano to Automate Deployments](https://www.digitalocean.com/community/tutorials/how-to-use-capistrano-to-automate-deployments-getting-started)
* [Deploying with Capistrano](http://guides.beanstalkapp.com/deployments/deploy-with-capistrano.html)

####What is manifesto for Agile Software Development?

#####How to use Adobe Photoshop?
#####How to use Adobe Illustrator?
#####How to use Adobe Premiere?
####How to build a design Machine?

####Who is Chad Fowler?
book [the passionate programmer](https://www.youtube.com/watch?v=CkfjCef-iYI)

####How bad are you 3 years ago? So what have you learned?

####What is first level? What is next level?
* Hardcore Linux
* Mobile development
* Server-side Functional programming
####What is on cn7web?
* [s](http://cn7web.com/s/index.html) deploy [ssh://sses80@cn7web.com/home/sses80/repo/site.git] [bitbucket](https://bitbucket.org/learning_group/single) source

####What is in mac/dev?
* [slim](http://www.slimframework.com/) a micro framework for PHP
* [Single](https://themeforest.net/item/master-one-page-html-5-portfolio-template/10671506) One Page HTML 5 Portfolio Template
* [PyroCMS](https://pyrocms.com/documentation)
* [OctoberCMS]() installoctober.dev/backend/backend

####How to use slack?
* [Enabling SAML-based single sign-on](https://get.slack.help/hc/en-us/articles/203772216-Enabling-SAML-based-single-sign-on)
* [Sign in with Slack](https://get.slack.help/hc/en-us/articles/218891278-Sign-in-with-Slack)
* [Connecting your tools to Slack](https://get.slack.help/hc/en-us/articles/223431088-Connecting-your-tools-to-Slack)

####How to use VirtualBox?
* [Failed to open/create the internal network Vagrant on Windows10] (http://stackoverflow.com/questions/33725779/failed-to-open-create-the-internal-network-vagrant-on-windows10) after upgrade VirtualBox
####How to use Vagrant?


####How to refresh Homestead after making changes to the Homestead.yaml
* I always call `vagrant global-status` to get the Id of my homestead machine, then call `vagrant provision [id]` to redo the provision-er.

####How to use VMware?

####How to place the ~/.composer/vendor/bin directory in your PATH?
Laravel installation: [bash](http://stackoverflow.com/questions/25373188/laravel-installation-how-to-place-the-composer-vendor-bin-directory-in-your)
[laravel storage permissions](https://laracasts.com/discuss/channels/general-discussion/laravel-framework-file-permission-security)

####What is AdminLTE?
* [Control Panel Template](https://almsaeedstudio.com/)

####How to use AdminLTE Control Sidebar?
* Control sidebar is the right side bar. It can be used for many purposes and is extremely easy to create. The sidebar ships with two different show/hide styles. The first allows the sidebar to slide over the content. The second pushes the content to make space for the sidebar. Either of these methods can be set through the Javascript options.

####How to use AdminLTE box component?
* Box The box component is the most widely used component through out this template. You can use it for anything from displaying charts to just blocks of text. It comes in many different styles that we will explore below.

####How to use github?
* [Exploring a Repository](https://egghead.io/lessons/javascript-exploring-a-repository) Watch (Notify), Start (Bookmark), Fork (). Issues (), Pull requests (merge), Wiki (document), Pulse (how active), Graphs (contributors)
* [Getting Started - First-Time Git Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup), [Git-Basics-Recording-Changes-to-the-Repository](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository), On github repo`t`(You’ve activated the file finder.) [global .gitignore](https://help.github.com/articles/ignoring-files/)
* [How to authenticate with GitHub using SSH ](https://egghead.io/lessons/javascript-how-to-authenticate-with-github-using-ssh)
1. `ssh-keygen -t rsa -b 4096 -C you@email.com`
2. `ssh-agent -s`,
3. `ssh-add ~/.ssh/id_rsa`
4.  win `clip < ~/.ssh/id_rsa.pub`, mac `pbcopy < ~/.ssh/id_rsa.pub`
* Find Identifying How to Contribute to an Open Source Project [What-oss](https://medium.com/@kentcdodds/what-open-source-project-should-i-contribute-to-7d50ecfe1cb4#.sshn9kl8i) **You contribute best to something you use regularly** [Contributing Guidelines](https://github.com/blog/1184-contributing-guidelines)
* [How to Fork and Clone a GitHub Repository ](https://egghead.io/lessons/javascript-how-to-fork-and-clone-a-github-repository), after fork add original Repo as upstream 
1. `git remote add upstream URL(use SSH)`
2. `git fetch upstream`
3. `git branch --set-upstream-to=upstream/master master`

* Setting up the project locally
1. `git checkout -b pr/test`
2.  `git show-branch --current`
3.   [CONTRIBUTING.md / Set up instructions](https://github.com/sses79/stack-overflow-copy-paste/blob/master/CONTRIBUTING.md#set-up-instructions)

* [How to create a Pull Request on GitHub?](https://egghead.io/lessons/javascript-how-to-create-a-pull-request-on-github)
1. `git diff`
2.  `git add .` `git commit -m 'text'` (hook will work) 
3. `git commit --no-verify` (Skip Git commit hooks)
4.  `git push origin pr/test`
5.  remote `git push --set-upstream(-u) origin pr/test`
6.  from remote **'new pull request'** *compare across forks* *head fork:* *compare:branch*
7. Collaborate on a Pull Request **codecov-io** 
8. Update a Pull Request **travis** `cat .travis.yml`
9. commit message standards `"<type>(<scope>): <subject>"`
10. rebase a git Pull Request branch 
11. `git fetch upstream` 
12. `git rebase upstream/master`
13. If need merging `git diff` editor fix, then `git add .`
14. `git rebase --continue` or back to your start `git rebase --abort`
15.  If `git push` will rejected by default, so `git push -f`

*[How to squash multiple git commits](https://egghead.io/lessons/javascript-how-to-squash-multiple-git-commits) rebase is rewriting history(log)
1. `git log` find commit hash `git rebase -i hash`
2.  edit commit to combine 2 commit into 1, use `squash`

####`php artisan migrate:rollback` error?
* `composer dump-autoload` the "framework" does not "know" about your new class.

```php
<?php
function sum(a, b){
    return a + b;
}
echo 12 * sub(1,2);
```