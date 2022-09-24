# Attack is the best defense

## Resource

- [Network sniffing](https://www.lifewire.com/definition-of-sniffer-817996)
- [ARP spoofing](https://www.veracode.com/security/arp-spoofing)
- [Connect to SendGrid’s SMTP relay using telnet](https://docs.sendgrid.com/ui/account-and-settings/troubleshooting-delays-and-latency)
- [What is Docker and why is it popular?](https://www.zdnet.com/article/what-is-docker-and-why-is-it-so-darn-popular/)
- [Dictionary attack](https://en.wikipedia.org/wiki/Dictionary_attack)

## Tasks

<p align="center">
  <img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/01c5a1e3f29d290b188d34be5cf534d3255058a7.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220924%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220924T105305Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=58dbc0cd10dd8570c14c8700aea549cc35214ea37b604460448b2b3c0377ad29" />
</p>
* Task 0 : ```0. ARP spoofing and sniffing unencrypted traffic```


Security is a vast topic, and network security is an important part of it. A lot of very sensitive information goes over networks that are used by many people, and some people might have bad intentions. Traffic going through a network can be intercepted by a malicious machine pretending to be another network device. Once the traffic is redirected to the malicious machine, the hacker can keep a copy of it and analyze it for potential interesting information. It is important to note that the traffic must then be forwarded to the actual device it was supposed to go (so that users and the system keep going as if nothing happened).

Any information that is not encrypted and sniffed by an attacker can be seen by the attacker - that could be your email password or credit card information. While today’s network security is much stronger than it used to be, there are still some legacy systems that are using unencrypted communication means. A popular one is ```telnet```.

In this project, we will not go over ARP spoofing, but we’ll start by sniffing unencrypted traffic and getting information out of it.

 Sendgrid offers is an emailing service that provides state of the art secure system to send emails, but also supports a legacy unsecured way: ```telnet```. You can create an account for free, which is what I did, and sendan email using ```telnet```:


* Task 2: ```Dictionary attack```
