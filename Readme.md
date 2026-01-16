Task-4A:

WAF Tasks: 
Attach WAF Web ACL to ALB
Add rule to block traffic from a specific IP (laptop ip)
Test application access before / after WAF rules

1) I created Load balancer with target Gropu and i given one instance as a target in the target group

   <img width="1366" height="768" alt="Loadbalancer" src="https://github.com/user-attachments/assets/afb0980b-de93-4392-8935-e24866baa3cd" />

   <img width="1366" height="768" alt="Targetgroup" src="https://github.com/user-attachments/assets/75ad7fab-b6d5-4bbb-a65b-c7670604a867" />



2) I created AWF where i created rule to block the particular IP, so that my application is can not be accessible from that particular IP

    <img width="1366" height="768" alt="wafShield" src="https://github.com/user-attachments/assets/938af578-0287-4c63-9309-34e9251d792d" />



3) Below are the images that indicates accessing of application before WAF Rule, and accessing of application after WAF rule configured

    <img width="1366" height="768" alt="BeforeWAF" src="https://github.com/user-attachments/assets/9281c9d7-429e-4747-8842-7603afdd762d" />

    <img width="1366" height="768" alt="AfterWAFRule" src="https://github.com/user-attachments/assets/b56dc711-f16f-4ddd-af31-56182a24444d" />


 



    
    
