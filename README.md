opentsdb-vagrant-box
====================

Work In Progress: [Vagrant](http://vagrantup.com/) box to easily get [OpenTSDB](http://opentsdb.net/ "OpenTSDB") up and running through Vagrant (with a [Chef](http://wiki.opscode.com/display/chef/Home) provisionning)

Done so far:
* install  HBase as listed at [OpenTSDB/Setup HBase](http://opentsdb.net/setup-hbase.html)
* start HBase if needed
* install OpenTSDB from source.
* create OpenTSDB hbase tables (only if needed)
* install tcollector (dedicated recipe opentsdb::tcollector)

Todo:

* start a TSD process
* start sample metrics gathering