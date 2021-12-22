messenger.h and messenger.cpp provide the functionality for an asynchronous two-way messaging system. 
Mutex locking is utilized here to be able to utilize the full functionality of the messaging system and eliminating race conditions.

main.cpp drives the application and outputs messages into a local file. This can be plugged into a webserver in order to provide 
two-way functionality.
