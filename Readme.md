
## BM

  Simple bash CLI benchmarks persisted by your _~/Dropbox_.

## Install

```
$ make install
$ make uninstall
```

## Example

  Add a bookmark:
  
    $ bm add http://subtlepatterns.com "tiling background images" design textures

  Open it later:

    $ bm subtle

  Search for design related bookmarks:

  ![cli benchmarks](http://f.cl.ly/items/1r3t1r0T283D1V04133v/Screen%20Shot%202012-03-15%20at%204.43.11%20PM.png)

## Usage

```

Usage: bm [options] [cmd]

Commands:

  # add a bookmark with the given url, description, and optional tags
  $ bm add <url> [desc] [tag...]

  # open the first bookmark matching <query>
  $ bm open <query>
  $ bm <query>

  # search the bookmarks via full-text <query>
  $ bm search <query>

  # list bookmarks available
  $ bm list
  $ bm ls
  $ bm

  # clear all bookmarks
  $ bm clear

Options:

   -V, --version   output bm version
   -h, --help      output this help information

```