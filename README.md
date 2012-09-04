Monitoring ElasticSearch with Opsview
============================

This repository contains an Opsview (<http://www.opsview.com>) plugin written in Perl for monitoring ElasticSearch (<http://www.elasticsearch.org/>) using the Cluster Health API (<http://www.elasticsearch.org/guide/reference/api/admin-cluster-health.html>).

The intention is to add stats / status information.

Brief instructions
------------------
1. Copy *check_elasticsearch* to */usr/local/nagios/libexec*
2. Ensure that *check_elasticsearch* is executable (using `chmod +x`)
3. You will need to have the *JSON* CPAN module (`sudo cpan -i JSON.pm`)
4. Look at the usage instructions (`./check_elasticsearch -h` or look at the Plugin help within Opsview)

