# Redis-Based Caching System

## Introduction

This project demonstrates the implementation of a caching
system using Redis and Python. The primary goal is to explore
how Redis can be used as a simple key-value store for caching data,
while also providing additional features like tracking method calls
and keeping a history of inputs and outputs.

The project covers:
- **Caching Data**: Storing and retrieving data in Redis using
		    generated keys.

- **Tracking Method Calls**: Monitoring how many times specific
			     methods are called.
- **Logging Input and Output**: Recording the input arguments and
			        return values for methods.

- **Replay Functionality**: Displaying the history of method calls,
			    including the inputs provided and the
			    outputs returned.

The caching system is built using Python and the `redis-py` library,
which interacts with a Redis server to manage the cache.

This project is a good demonstration of using Redis in Python
for simple caching purposes, as well as for learning more about
decorators and Redis commands.
