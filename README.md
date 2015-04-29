# How to build the Gitbook with gitbook-cli

Need the package fo git, make, node.js, npm and gitbook-cli.

![My private GitBook](images/my-private-gitbook.png)

## Setup

1. Install node.js and npm package.

        # Mac OSX.
        $ brew install node npm

        # Ubuntu.
        $ apt-get install nodejs npm

1. Install gitbook-cli package.

        $ sudo npm install -g gitbook-cli

1. Check version.

        $ sudo gitbook -V
        0.3.3

## Get repository.

Get *MyBook* with git.

    $ git clone git@example.tw:MyBook.git

## Build

1. Go to MyBook project.

        $ cd MyBook

1. Build static HTML.

        $ make

1. Review result at local.

        $ make review

## Reference

- [GitbookIO/gitbook-cli | GitHub](https://github.com/GitbookIO/gitbook-cli)
- [深入淺出 GitBook 寫作與自助出版，電子書也能多人協作 by lyhcode | CodeData](http://www.codedata.com.tw/social-coding/gitbook-self-publishing/)
- [gitbook | npm](https://www.npmjs.com/package/gitbook)
