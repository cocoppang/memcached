# Memcached with local file io

Driving Memcached with local file io instead of socket protocol.

## Limitation

* Do not use the libevent library.
	* Hash expansion does not support.

## Usage

./memcached -u root -B file -t [thread_num] -m 2048 -o hashpower=23

