## Scaling in Software Systems


A load balancer became crucial as the team faced performance and scaling issues, which significantly affected the application’s responsiveness and performance.

A Load balancer is a device that sits between the user and the server group and acts as an invisible facilitator, ensuring that all resource servers are used equally. It directs and controls internet traffic between the application servers and their visitors or clients.

Vertical Scaling involves enhancing the capacity of a single server by adding more resources—such as CPU, RAM, or storage. This approach is relatively simple to implement, as it doesn't require modifications to the application architecture.
However, it has limitations like higher costs and the risk of hitting hardware limitations, which can hinder further scaling efforts.

Horizontal scaling involves adding more servers to distribute the load across multiple machines. This method provides greater flexibility, improves fault tolerance, and is generally more cost-effective for handling increased traffic over time.

After thorough analysis and careful consideration, Load balancers will be crucial in a horizontally scaled system, as they distribute incoming traffic across multiple servers, ensuring no single server becomes a bottleneck. This distribution not only enhances performance, flexibility and scalability but also improves system resilience, as the failure of a single server does not compromise the entire system.


### References

* [What is Load Balancers](https://www.f5.com/glossary/load-balancer)
  
* [Load Balancers and Their Role in Scaling](https://aws.amazon.com/what-is/load-balancing/)
  
* [Vertical vs Horizontal Scaling](https://www.cloudzero.com/blog/horizontal-vs-vertical-scaling/#:~:text=While%20horizontal%20scaling%20refers%20to,%2C%20storage%2C%20or%20network%20speed.)
