# stacked-pr-lab

A sandbox for watching how a stack of pull requests merges.

Two pull requests, each appending one line to `notes.md`, stacked so that the
second builds on the first. CI is a single job that prints the file, so a run
finishes in seconds.
