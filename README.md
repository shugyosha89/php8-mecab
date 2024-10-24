php-mecab: MeCab binding for PHP 8
==================================

ABOUT
-----

I have updated this extension work without warnings and deprecation notices on PHP 8.1 & 8.2.

INSTALL
-------

To compile the extension, you can use the following steps:

1. `git clone https://github.com/shugyosha89/php8-mecab.git`
2. `cd ./php8-mecab/mecab`
3. `phpize`
4. `./configure --with-php-config=/usr/local/bin/php-config --with-mecab=/usr/local/bin/mecab-config` (config parameters are optional)
5. `make`
6. `make install`

In order to use it, you will have to enable the extension.
For example by adding `extension=mecab.so` to your php.ini file.

To understand how to use the MeCab bindings, see the `mecab/examples` directory.

LICENSE
-------
```
Copyright (c) 2006-2015 Ryusuke SEKIYAMA. All rights reserved.

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
```
