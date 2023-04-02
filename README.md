# python-cli-csv-to-filebeat-multi-node-elk-without-ssl-dsl-body-simple

## Description
Reads a csv file into a multi node elk stack for data in `dog-demo` document.

Uses elasticsearch client, 2 ways, and dsl to compare some query examples.

## Tech stack
- python
    - elasticsearch
    - elasticsearch_dsl
- elasticsearch
- kibana
- logstash
- filebeats

## Docker stack
- python
- elasticsearch
- logstash
- kibana
- filebeats

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [DSL Search](https://medium.com/@kartik.puri95/a-ninja-way-to-use-elasticsearch-with-python-40a1e841e859)
- [DSL Range](https://stackoverflow.com/questions/43368586/range-query-in-elasticsearch-dsl-by-integer-field)