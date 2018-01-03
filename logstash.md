##Logstash
* logstash can be used for read logs stream (e.g filebeats), parse it(strongly using grok filters) and send it to elastic search.
* you can use our two example file `log4j-file.conf` (for read directly from log file) or `log4j-filebeats.conf` (for read from filebeats outputstream) and parse them using defined `grok` filters and then send them to `elasticsearch`.
* run with `./logstash-5.6.2/bin/logstash -f ../conf-files/log4j-filebeats.conf` or  `./logstash-5.6.2/bin/logstash -f ../conf-files/log4j-file.conf`
