---
title: "Amazon API Gateway + Route53"
menutitle: "Amazon API Gateway + Route53"
chapter: false
weight: 1
pre: "<b></b>"
tags: [Warm Standby]
type: Lab
awsServices:
 - Amazon API Gateway
---

### Objective

This exercise shows the steps to quickly set up your APIs in more than one AWS Region and allow them to behave in an active-passive way by receiving requests transparently from your customers.

**Required knowledge:**

* Basic usage of the AWS CLI
* Basic concepts of load balancers 

**By the end of this exercise, you will be able to:**

* Set up an API in two or more regions
* Set up a DNS record to dynamically routing your APIs transparently to your customers

**Estimated Duration:** 40 minutes

**Approximate Cost**: 3 USD

![Arquitetura API Gateway](/images/apigw-lab-architecture.png)

### Execution

{{< tabs name="labs_types" >}}  
{{< tab name="AWS CloudShell" include="cloudshell" />}}  
{{< /tabs >}}

### Conclusion

With this exercise, we were able to understand how to set up a private API in Amazon API Gateway, deploy the API to more than one region, and create a routing policy for your DNS records associated with your API endpoints.

[Alternative to Custom Domain Name](https://georgemao.medium.com/enabling-private-apis-with-custom-domain-names-aws-api-gateway-df1b62b0ba7c)
