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

1. Install **[calibre](http://calibre-ebook.com/about)** for build pdf, epub and mobi.

1. Link **calibre command line tool**.

        # Mac OSX.
        $ ln -s /Applications/calibre.app/Contents/MacOS/ebook-convert /usr/local/bin/

## Get repository.

Get *MyBook* with git.

    $ git clone git@github.com:chusiang/how-to-build-the-gitbook-with-gitbook-cli.git

## Build

1. Go to `MyBook` project.

        $ cd ${MyBook}

1. Build static HTML.

        $ make

1. Build PDF.

        $ make pdf

1. Build epub for iDevice.

        $ make epub

1. Build mobi for Kindle.

        $ make mobi

1. Review result at local.

        $ make review

1. Clean.

        $ make clean

## Reference

- [GitbookIO/gitbook-cli | GitHub](https://github.com/GitbookIO/gitbook-cli)
- [深入淺出 GitBook 寫作與自助出版，電子書也能多人協作 by lyhcode | CodeData](http://www.codedata.com.tw/social-coding/gitbook-self-publishing/)
- [gitbook | npm](https://www.npmjs.com/package/gitbook)
- [Convert to PDF - Need to install ebook-convert from Calibre · Issue #333 · GitbookIO/gitbook](https://github.com/GitbookIO/gitbook/issues/333)
