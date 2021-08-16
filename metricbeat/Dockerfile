FROM docker.elastic.co/beats/metricbeat:7.14.0

RUN metricbeat setup -E setup.kibana.host=192.168.10.115:29601 -E output.elasticsearch.hosts=["192.168.10.115:29200"]

