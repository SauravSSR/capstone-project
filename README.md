<h1>PROJECT</h1>

<h2>Infra Optimization</h2>
<h3> Description: </h3>

Create a DevOps infrastructure for an e-commerce application to run on high-availability mode.
Background of the problem statement:
A popular payment application, EasyPay where users add money to their wallet accounts, faces an issue in its payment success rate. The timeout that occurs with
the connectivity of the database has been the reason for the issue.
While troubleshooting, it is found that the database server has several downtime instances at irregular intervals. This situation compels the company to create their own infrastructure that runs in high-availability mode.
Given that online shopping experiences continue to evolve as per customer expectations, the developers are driven to make their app more reliable, fast, and secure for improving the performance of the current system.

<h3> Implementation requirements: </h3>
<p>    1. Create the cluster (EC2 instances with load balancer and elastic IP in case of AWS) 
<p>    2. Automate the provisioning of an EC2 instance using Ansible or Chef Puppet 
<p>    3. Install Docker and Kubernetes on the cluster 
<p>    4. Implement the network policies at the database pod to allow ingress traffic from the front-end application pod 
<p>    5. Create a new user with permissions to create, list, get, update, and delete pods 
<p>    6. Configure application on the pod 
<p>    7. Take snapshot of ETCD database 
<p>    8. Set criteria such that if the memory of CPU goes beyond 50%, environments automatically get scaled up and configured 
    
<h3> Tools Used: </h3>
<p>    1. EC2 
<p>    2. Kubernetes 
<p>    3. Docker 
<p>    4. Ansible or Chef or Puppet
