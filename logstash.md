## Logstash
* logstash can be used for read logs stream (e.g filebeats), parse it(strongly recommend using grok filters) and send it to elastic search.
* you can use our three example file `log4j-file.conf` (for read directly from log4j log file) or `log4j-filebeats.conf` (for read from filebeats outputstream) or `csv-config.conf` (for read from .csv files) and parse them (using defined `grok` filters or simple filter) and then send them to `elasticsearch`.
* run with `./logstash-5.6.2/bin/logstash -f ../conf-files/log4j-filebeats.conf`
