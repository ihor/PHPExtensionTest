Hello world PHP extension written by this tutorial http://www.tuxradar.com/practicalphp/20/0/0


Do the following to use this extension:
```
phpize
./configure --enable-hello
make
```


It will create hello.so extension in the modules directory.


Add the path to it in your php.ini:
`extension="<...>/hello.so"`

Then try to do the following:
```
php -r "hello_print();"
php -r "hello_repeat('test', 5);"
php -r "echo hello_factorial(5);"
```
Tested with PHP 5.3