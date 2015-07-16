This is a copy of 
git@github.com:chokkan/simstring.git

The algorithm can be found at:
http://www.xmailserver.org/diff2.pdf

The implementation can be found at:
http://chokkan.org/software/simstring/

And a use case example at:
http://chokkan.org/software/simstring/swig/index.html#sample


So far I could only get this to work on linux (some compliation issues on mac...)



To use,

$ sudo apt-get install automake swig
$ git clone git@github.com:oinbar/simstring.git
$ cd simstring
$ sudo sh ./autogen.sh
$ sudo ./configure
$ cd swig/python
$ sudo sh ./prepare.sh --swig
$ sudo python setup.py build_ext --inplace
$ sudo python setup.py install