These bash scripts use RRDtool to log and graph:

* CPU temperature

I run these scripts using crontab:

    */5 * * * * path/to/script/./temperature

I found [the `rrdtool` documentation](https://oss.oetiker.ch/rrdtool/doc/index.en.html) and the [Beginners' Guide](https://linux.die.net/man/1/rrd-beginners) helpful in writing these scripts.
