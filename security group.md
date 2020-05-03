# **Security Group**
- *A security groups acts as a virtual firewall that controls the traffic for one or more instances.*
- *When we launch an instance we can specify one or more security groups; otherwise we can use the default security group.*
- *After that we can set up ports and protocols, which remain open for users and computers over the internet.*
- *Security Groups controls both inbound and outbound traffic.*
- *For each security group, we add rules that control the inbound traffic to instances, and a separate set of rules that control the outbound traffic.* 

## Inbound rule
- *Inbound rules filter traffic passing from the network to the local computer based on the filtering conditions specified in the rule.*
- *When we create a security group, it has no inbound rules. Therefore, no inbound traffic originating from another host to your instance is allowed until you add inbound rules to the security group.*

## Outbound rule
- *Outbound rules filter traffic passing from the local computer to the network based on the filtering conditions specified in the rule.* 
- *By default a security group includes an outbound rule that allows all outbound traffic.*
  *We can remove the rule and add outbound rules that allow specific outbound traffic only.*
  
