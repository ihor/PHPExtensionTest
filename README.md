Hello world PHP extension written by this tutorial http://www.tuxradar.com/practicalphp/20/0/0


Do the following to use extension:
`phpize`
`./configure --enable-hello`
`make`


It will create hello.so extension in the modules directory.


Add the path to it in your php.ini:
`extension="<...>/hello.so"`


Tested with PHP 5.3