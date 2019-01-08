# Memcached with local file io

Driving Memcached with local file io instead of socket protocol.

## Limitation

* Do not use the libevent library.
	* Hash expansion does not support.



