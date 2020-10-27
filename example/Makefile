all: sample

sample: sample.cc
		g++ -o $@ $<  ../build/libleveldb.a -lpthread -I ../include -std=c++11

clean:
		rm -rf sample testdb
