# pusht and popt

Push and pop tasks in the command line.

We all end up [Yak Shaving](https://rationalwiki.org/wiki/Fun:Yak_shaving) now and again. Push your tasks in a stack so that you don't foget what you were doing before you were doing that thing you were just doing.

## Installing
Clone this repo and copy `pusht` and `popt` to your $PATH. Then set environment variable PUSHPOPT=/path/to/anywhere/pushpopdb.txt, this path will be where pusht saves your tasks. Add this to your `bashrc` file so your task database persists across sessions.

# Use

Need to do something? Just run `pusht something`

Want to check what you need to do? `popt -l`

Done with that thing? Run `popt`


