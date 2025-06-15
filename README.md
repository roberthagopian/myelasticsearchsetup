Starting this ELK lab off by setting up a VPC 2.0 Network in the cloud

![alt text](https://i.imgur.com/zBmLoU7.png)

Then spinning up a ubuntu server and attaching it to that Cloud VPC Network.

![alt text](https://i.imgur.com/9u0B44W.png)

I then SSH in and installed elasticsearch on the server. I edited the elasticsearch.yml network host file and added the servers public IP, as it defaults to localhost.

![alt text](https://i.imgur.com/BEtuZcd.jpeg)

I then added a firewall group with my own ip so only I could ssh in.

![alt text](https://i.imgur.com/PJMI81m.png)


The last step was starting my elasticsearch.service and subsequently checking the service with a systemctl status elasticsearch.service 

![alt text](https://i.imgur.com/BNtEVDy.jpeg)

