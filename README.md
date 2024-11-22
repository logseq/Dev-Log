## Description

Repository for Dev Log

## Usage

Setup this up once for the desktop app:

* Create a graph called 'Dev Log'.
* Delete the graph: `rm -rf ~/logseq/graphs/Dev\ Log`
* Clone this repository in its place: `cd ~/logseq/graphs && git clone https://github.com/logseq/Dev-Log Dev\ Log`
* Run the dev command `Replace graph with its db.sqlite file` and choose `Dev Log`.

Whenever someone else makes a change to the graph:
* `git pull`
* Run the dev command `Replace graph with its db.sqlite file` and choose `Dev Log`.

To push your changes to GitHub, save them with `Cmd-S` to persist them to disk. Then git commit and push the file changes.