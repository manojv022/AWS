## `routing policy`
A setting for records that determines how Route 53 responds to DNS queries. Route 53 supports the following routing policies:

**Simple routing policy** – Use to route internet traffic to a single resource that performs a given function for your domain, for example, a web server that serves content for the example.com website.

**Failover routing policy** – Use when you want to configure active-passive failover.

**Geolocation routing policy** – Use when you want to route internet traffic to your resources based on the location of your users.

**Geoproximity routing policy** – Use when you want to route traffic based on the location of your resources and, optionally, shift traffic from resources in one location to resources in another.

**Latency routing policy** – Use when you have resources in multiple locations and you want to route traffic to the resource that provides the best latency.

**IP-based routing policy** – Use when you want to route traffic based on the location of your users, and have the IP addresses that the traffic originates from.

**Multivalue answer routing policy** – Use when you want Route 53 to respond to DNS queries with up to eight healthy records selected at random.

**Weighted routing policy** – Use to route traffic to multiple resources in proportions that you specify.

![image](https://github.com/user-attachments/assets/d0506b0a-c9a1-428a-a812-2732233ba4ab)


### Health Check:
![image](https://github.com/user-attachments/assets/e559942b-5ebe-4dc8-87b9-7e28ec8d628e)


### Route 53 Resolver:
![image](https://github.com/user-attachments/assets/65acf6e4-6a72-4721-b77d-38adf899b097)

