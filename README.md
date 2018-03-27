# git-open

Tiny script that opens github repository in the browser.

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

## Lisence

MIT License.
