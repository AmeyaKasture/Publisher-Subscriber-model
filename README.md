# Publisher-Subscriber model
 Comparing the efficiency of pub-sub models between c++ and go

# C++ Redis Pub/Sub Tester

This C++ project demonstrates the use of Redis Pub/Sub functionality using the [redis-plus-plus](https://github.com/sewenew/redis-plus-plus) library.

## Prerequisites

Before you can build and run this project, ensure that you have the following dependencies installed:

- **C++ Compiler:** This project uses g++ as the compiler.
- **C++ Standard:** The project is configured to use C++17 standard.
- **pthread:** The project uses the POSIX Threads library, so make sure it is available on your system.
- **Redis C++ Library:** [redis-plus-plus](https://github.com/sewenew/redis-plus-plus) is included in the project. You may need to build and link it. The provided paths for `REDIS_LIB` and `HIREDIS_LIB` assume specific locations, so modify them if necessary.

## Build Instructions

```bash
- **Testing** For testing.
$ make test 

- **Inititalisation 1** First way of initialisation.
$ make  pubsub

- **Initialisation 2 ** Second way of initialisation.
$ make pubsub2 

- **Cache** For setting up cache using redis .
$ make cache

