# git-open

Tiny script that opens github repository in the browser.

## Requirements

- Mac OS X

## Install

    $ curl 'https://raw.githubusercontent.com/arai-ta/git-open/master/git-open' -o your/path/bin/git-open
    
    $ chmod +x $_

## Usage

    $ cd repo
    
    $ git open
    # ==> https://github.com/your/repo
    
    $ git checkout develop
    
    $ git open README.md
    # ==> https://github.com/your/repo/blob/develop/README.md

### Options

* `-p`, `--copy` : Copy URL to clipboard instead of opening bworser.
* `-h`, `--hash` : Use abbreviated commit hash as a part of URL, instead of branch name.
* `-l`, `--long-hash` : Use full commit hash as a part of URL, instead of branch name.

## Lisence

MIT License.
