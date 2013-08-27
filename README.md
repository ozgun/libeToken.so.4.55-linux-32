libeToken.so.4.55-linux-32
==========================

Aladdin eToken driver paketinden(pkiclient-full_4.55-33_i386.deb) çıkartılan libeToken.so.4.55-linux-32 dosyası.

libeToken.so.4.55 dosyası indirilip /usr/lib altına kopyalanır ve gerekli linkler şu şekilde oluşturulur:

````sh
$ cd /usr/lib
$ sudo ln -s libeToken.so.4.55 libetpkcs11.so
$ sudo ln -s libeToken.so.4.55 libeTSapi.so
$ sudo ln -s libeToken.so.4.55 libeTPkcs11.so
$ sudo ln -s libeToken.so.4.55 libeToken.so
$ sudo ln -s libeToken.so.4.55 libeToken.so.4
````
