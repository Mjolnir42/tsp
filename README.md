tsp -- Timestamp Prefix
=======================

Simple shell tool to prefix lines of text with timestamps.
Reads from `STDIN`, writes to `STDOUT`.

Example
-------

```
% echo "Testline 1" | tsp
2016-03-29T23:04:38.587Z Testline 1

% echo "Testline 2" | tsp -l
2016-03-30T01:04:40.617+02:00 Testline 2
```
