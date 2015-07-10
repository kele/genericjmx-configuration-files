Configuration files for GenericJMX
----------------------------------

### Example usage
If you want to use GenericJMX for Cassandra monitoring, you have to:

1. Set `CASSANDRA_HOST` and `CASSANDRA_PORT` in `cassandra.conf` file.
2. Include `cassandra.conf` in your main collectd configuration file.
3. Add contents of `cassandra_types.db` to collectd's `types.db` file (usually
   `/usr/share/collectd/types.db`).
4. Restart collectd.

