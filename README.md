# Redis
A git repository to learn Redis

## Setup

Install Homebrew for MacOs

Can be started directly on Linux

In windows, install Windows Subsystem for Linux (Ubuntu)

## Installation

  To install

    sudo apt-get install redis

  To start redis server

    redis-server

### Redis Commands

  To start Redis Command Line Interface

    redis - cli

  To get out of redis cli

    quit

  To set a key vaue

    set <key> <value>
      Ex: set name kyle

  To get a value

    Ex: get name

  To delete a key

    Ex: del name

  To check whether a key exists or not

    Ex: exists name

  To find all the keys

    keys *

  To clear everything out

    flushall

  To get the TTL (Time to live)

    Ex: ttl name

  To set an expiration for existing key

    Ex: expire name 10 # expires in 10 seconds

  To set an expiration 

    Ex: setex name 10 kyle

  To push an element from left to the array

    Ex: lpush friends john 
        #friends('john')

  To push an element from right to the array

    Ex: rpush friends john   

  To get the elements 

    lrange <list> <start> <end>
    Ex: lrange friends 0 -1

  To take out first element from the left

    Ex: lpop friends

  To take out first element from the right

    Ex: rpop friends

  To add an element to the set

    sadd <key> <value>
    Ex: sadd hobbies "weight lifting"
    # sets are unique

  To get all the elements of a set

    Ex: smembers hobbies

  To remove a value from the set

    Ex: srem hobbies "weight lifting"

  To set a hash value

    Ex: hset person name kyle

  To get a hash value

    Ex: hget person name

  To get all

    Ex: hgetall person

  To check whether an element exists in a hash

    Ex: hexists person name

  To del a key

    Ex: hdel person age

  

  

  




    
