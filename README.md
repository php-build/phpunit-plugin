
PHPUnit Plugin for php-build
============================

## What is this?

This small script hooks into [php-build](https://github.com/CHH/php-build) 
and automatically installs PHPUnit on each Build, so you don't have to.

## What is it good for?

Ideal for testing a Library with multiple PHP Versions. I've scratched
my own itch with this. 

Before, I had to install on each and every PHP Build I wanted to test 
with PHPUnit. Now I only have to build my PHP versions with `php-build` 
and I'm done.

## Install

Just copy the `share` directory into your `php-build` installation, or
link `share/php-build/after-install.d/phpunit` to
`share/php-build/after-install.d/` in your `php-build` installation.

## License

The MIT License

Copyright (c) 2011 Christoph Hochstrasser

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

