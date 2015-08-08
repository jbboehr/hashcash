# hashcash

[![Build Status](https://travis-ci.org/jbboehr/hashcash.svg?branch=master)](https://travis-ci.org/jbboehr/hashcash)

[hashcash](http://www.hashcash.org/), converted to autoconf.

## Installation

### Ubuntu 

```bash
sudo apt-get install autoconf automake gcc git-core libtool m4 make pkg-config
git clone https://github.com/jbboehr/hashcash.git --recursive
cd hashcash
autoreconf -fiv
./configure && make && sudo make install && sudo ldconfig
```

## License

See [the license file](https://github.com/jbboehr/hashcash/blob/master/LICENSE).

