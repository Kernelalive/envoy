Replace the content of this file with the content of the prefered use case.
	For the LoadBaLancer adjust the weights in the weighted cluster attribute and curl -v $(docker-machine ip default):8000/service/
	For the FireWall (Tcp Proxy) just put the Ip you want to block any requests to envoy in the source_ip_list attribute inside ""
