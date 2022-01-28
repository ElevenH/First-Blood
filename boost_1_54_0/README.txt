./bootstrap.sh --prefix=/usr/local
./b2 install --with=all


g++ syslogem.cpp -L/usr/local/lib -lboost_system
