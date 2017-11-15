# Configuring Router and Firewall Rules for Amazon Route 53 Health Checks<a name="dns-failover-router-firewall-rules"></a>

When Amazon Route 53 checks the health of an endpoint, it sends an HTTP, HTTPS, or TCP request to the IP address and port that you specified when you created the health check\. For a health check to succeed, your router and firewall rules must allow inbound traffic from the IP addresses that the Amazon Route 53 health checkers use\. \(In Amazon EC2, security groups act as firewalls\. For more information, see [Amazon EC2 Security Groups](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-network-security.html) in the *Amazon EC2 User Guide for Linux Instances*\.\) For the current list of IP addresses for Amazon Route 53 health checkers, for Amazon Route 53 name servers, and for other AWS services, see [IP Address Ranges of Amazon Route 53 Servers](route-53-ip-addresses.md)\. 