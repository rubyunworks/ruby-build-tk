# ruby-build-tk

ruby-build-tk provides additional build scripts for ruby-build that
include build Ruby's Tk extensions.


### Installing ruby-build-tk

First be sure to install ruby-build, then:

    $ git clone git://github.com/trans/ruby-build-tk.git
    $ cd ruby-build-tk
    $ ./install.sh

This will install ruby-build-tk into `/usr/local`. If you do not have
write permission to `/usr/local`, you will need to run `sudo
./install.sh` instead. If you installed ruby-build with a different
prefix by you will need to use the same setting of `PREFIX` environment
variable.


### Installing Ruby

To install a Ruby version, run the `ruby-build` command with the path
to a definition file and the path where you want to install it. (A
number of [built-in
definitions](https://github.com/sstephenson/ruby-build/tree/master/share/ruby-build)
may be specified instead.)

    $ ruby-build 1.9.3-rc1+tk8.5 ~/local/ruby-1.9.3-rc1+tk8.5
    ...
    $ ~/local/ruby-1.9.3-rc1+tk8.5/bin/ruby --version
    ruby 1.9.3dev (2011-09-23 revision 33323) [x86_64-linux]

You can use it with [rbenv](https://github.com/sstephenson/rbenv):

    $ ruby-build 1.9.3-rc1+tk8.5 ~/.rbenv/versions/1.9.3-rc1+tk8.5


### Version History

#### 2011-12-07

 * Initial public release.


### License

(The MIT License)

Copyright (c) 2011 Sam Stephenson / Thomas Sawyer

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
