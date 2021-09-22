
# Day 1 
## About Redis and CRUD operations 
What is REDIS ?
REDIS is an open source, in-memory data structure store, used as a database, cache and message broker.
Methods :-
  ### 1. SET
          It is used to set value in key in string format.
        "SET name 'satya' or satya"


### 2. GET
          It is used to find value of key.
         "GET keyName"


### 3. EXISTS
        It will check wether key exists or not. If exists then it will return 1 else 0.
        " EXISTS keyName"


### 4. KEYS *
      It prints all keys and not value.
      "KEYS "


### 5. FLUSHALL
      It delete's all keys and of-course value as well.
      "FLUSHALL"


### 6. DEL keyName
      It delete's a key named keyName.
      "DEL keyName"


### 7. TTL (Time to Live)
      It returns time on expire a key.
      If expire time is not set then it will return -1.
      " ttl keyName"


### 8. Expire
      It sets a time to expire.
      "expire keyName time (in sec)"


### 9. setex
      It will set a value in key with expire time.
      "setex keyName time value"

##  Array
### 10. LPUSH
push in left of array.
      push in left of array.

### 11. RPUSH
push in right of array.

### 12. LPOP
pop to left of array.

### 13. RPOP
      pop to right of array.
      "lpush arrayName value"

### 14. LRANGE
        It will print array from index a to b.
        If b is -1 then it will print a to last element of array.
        " LRANGE arr 0 -1"

## SET

### 15. SADD
      Add in set.
      " SADD setName value"

### 16. SMEMBERS
    It will prints all members of set.
   "SMEMBERS setName"

### 17. HSET
    " HSET objName keyName value"

### 18. HGET
    "Get value"

### 19. HGETALL
    "Get all value"

### 20. HDEL
    "Delete a key of object."
