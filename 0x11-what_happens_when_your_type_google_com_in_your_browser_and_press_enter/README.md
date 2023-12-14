# 0x11. What happens when you type google.com in your browser and press Enter

## Background Context
Being a Full-Stack Software Engineer means you’re comfortable interacting with any layer of the stack.

A way to easily assess this is to simply ask an engineer to explain how a software system works. They can have a general overview of the flow or can choose to dig deep in a certain area.

Let’s practice by exploring the infrastructure side (network, servers, security…) of the question.

![fullstack](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/298/aJPw3mw.jpg)

## 1. Everything's better with a pretty diagram 

Add a schema to your blog post illustrating the flow of the request created when you type https://www.google.com in your browser and press Enter.

The diagram should show:

    DNS resolution
    that the request hitting server IP on the appropriate port
    that the traffic is encrypted
    that the traffic goes through a firewall
    that the request is distributed via a load balancer
    that the web server answers the request by serving a web page
    that the application server generates the web page
    that the application server request data from the database

![example 1](https://i.imgur.com/i9ivkdo.png)
![example 2](https://i.imgur.com/R8R3sqC.png)

