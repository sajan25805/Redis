
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

-`GET KEY`: Retrieve the value of a KEY.
Example: GET Name => `"Sajan"`

-`DEL KEY`: Retrieve the value of a KEY.
Example: DEL Name  Result => `(integer) 1`

-`EXISTS KEY`: Check if a key exists in the redis database. Gives 1 for true and 0 for false.




