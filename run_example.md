# run_example

./build/SQLiteCpp_Example 
SQlite3 version 3.39.3 (3.39.3)
SQliteC++ version 3.02.00
SQLite database file 'test.db3' opened successfully
INSERT INTO test VALUES (NULL, "test")", returned 1
INSERT INTO test VALUES (NULL, "second")", returned 1
UPDATE test SET value="second-updated" WHERE id='2', returned 1
SELECT * FROM test :
row (1, "test")
row (2, "second-updated")
everything ok, quitting