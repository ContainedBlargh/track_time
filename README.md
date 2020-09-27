# track_time

A time-tracking tool that uses git and the filesystem to estimate how much time has been spent on a project.

It's a simple python scrip that is heavily inspired by [`git-hours`](https://github.com/kimmobrunfeldt/git-hours).

Unfortunately, I could never get `git-hours` to work on my setup, I decided to implement it myself.
I've also taken filesystem's creation date and last modified date for each file into account.
