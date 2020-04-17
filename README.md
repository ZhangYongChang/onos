1. docker run -t -d --name onos1 onosproject/onos:2.2.2

app activate org.onosproject.openflow
app activate org.onosproject.fwd

2. docker-compose up -d

3. mn --topo tree,2 --controller remote,ip=172.17.0.2




