
#### Redis Installation Command:
-`sudo apt-get install redis`

#### Starting Redis Server:
-`redis-server`
Note: Default port is `6379`

#### Opening Redis Server Terminal:
-`redis-cli`

### Basic Redis Commands.
-`quit`: quit the redis command Line Interface.

##### Note: Everything we store inside the redis will be string default.

-`SET KEY value`: Set the value of a KEY.
Example: SET Name Sajan
-`SETNX KEY VALUE` stores a string value only if the key doesn't already exist. Useful for implementing locks.

-`GET KEY`: Retrieve the value of a KEY.
Example: GET Name => `"Sajan"`
`MGET KEy`retrieves multiple string values in a single operation.


-`DEL KEY`: Retrieve the value of a KEY.
Example: DEL Name  Result => `(integer) 1`

-`EXISTS KEY`: Check if a key exists in the redis database. Gives 1 for `TRUE` and 0 for `FALSE` .

-`FLUSHALL`: Clear all tne things in the redis database.

-`KEYS pattern`: Return the key of certain patterns. 
Example : `KEYS *`: Return all the keys in the redis database.

 ************************ ListCommands ************************

-`LPUSH KEY VALUE` stores the value to the beginning of the list.
Example : `LPUSH NAME sajan`:  

-`LRANGE KEY START STOP`: Returns the value of the list from the start to the stop.
Example : `LRANGE NAME 0 -1`: Returns the value of the list from the index 0 to the last index of the list.  Here we got:
1) "HARI"
2) "sajan"











