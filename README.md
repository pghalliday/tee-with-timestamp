# tee-with-timestamp

Bash script to tee to a file and automatically add a timestamp to the name

Dependencies
------------

- tee

Usage
-----

```
./tee-with-timestamp.sh PREFIX SUFFIX
```

where:

```
PREFIX - text to prepend to timestamp
SUFFIX - text to append to timestamp
```

Example
-------

```
echo some text | ./tee-with-timestamp.sh ./myfile_ .txt
```

will create a file called `./myfile_YYYYMMDD-HHMMSS.txt` containing:

```
some text
```
