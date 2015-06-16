# OPK CLI: Simple CSV 

A cli for push data from a pipe to a csv. Contains support for streams.

Example:
```
> echo "42" | opk-cli-simple-csv/push
> echo "44" | opk-cli-simple-csv/push
> cat output.csv
2015-06-16 00:31:47,42
2015-06-16 00:31:48,44
```

Credits:
Stefan Unterhauser
R.J. Steinert

License: GPLv3
