# libmemcached 1.0.18
to compile ./configure --enable-memaslap
make LDFLAGS="-L/lib64 -lpthread"
sudo make install
sudo ldconfig /usr/local/lib
