Build docker:
docker run --name ubuntu -d pycontribs/ubuntu:latest sleep 600000

Build the server with the following command:
ansible-playbook -i inventory/prod.yml site.yml

The server contain:
JDK 11
ElasticSearch 7.10.1
Kibana 6.8.15