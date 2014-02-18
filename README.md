Murmur
======

Ansible role that installs and configures Murmur, the server component of the [Mumble voice chat software](http://mumble.sourceforge.net/). This role is designed to run on Ubuntu.

Role Variables
--------------

There are 44 role variables available, one for every single Murmur configuration option that can be set. All of the variables can be found in in the `mumble-server.ini.j2` template. The original Mumble documentation of each variable's function is located in the template file as well.

Running this role without overriding any of the variables will install the latest version of Murmur and configure it with the default values so it is ready for action!

License
-------

The MIT License (MIT)

Copyright (c) 2014 Joshua Lund

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Author Information
------------------

You can find me on [Twitter](https://twitter.com/joshualund), and on [GitHub](https://github.com/jlund/). I also occasionally blog at [MissingM](http://missingm.co).
