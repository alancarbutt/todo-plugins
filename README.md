# todo.txt-plugins

## My favorite plugins for todo.txt

I'm including the plugins that I use that I had to modify for use with todo.txt. These plugins are listed on the https://github.com/todotxt/todo.txt-cli/wiki/Todo.sh-Add-on-Directory site

I'm testing the code on my iMac running Big Sur

Thus far, I have had to fix the following plugins

* xp
    * Fixed several BASH specific issues that with the base code from Chris Jones that would not allow me to use the plugin
* setdue
    * Fixed BASH issues
    * Fixed sed call that in some instances deletes all contents in the todo.txt file
* again
    * Fix Documentation
* projectview
    * Just worked
* edit
    * Just worked
* recur
    * had to install perlbrew (https://perlbrew.pl/) to make this one work
    * cron was used to schedule the recurring tasks
* remind
    * worked out of the box
* revive
    * cleaned up some of the BASH script code
* schedule
    * cleaned up some of the BASH code
* stale
    * worked out of the box

More to come...

- [x] Fix xp code and documentation
- [x] Fix setdue issue where sed command deletes all TODOs in the todo.txt file
- [x] Fix BASH issues for again script
- [ ] Fix documentation for again script
