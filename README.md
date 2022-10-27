# Linux Administration Cookbook

<a href="https://www.packtpub.com/virtualization-and-cloud/linux-administration-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781789342529 "><img src="https://d255esdrn735hr.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/B11196.png" alt="Linux Administration Cookbook" height="256px" align="right"></a>

This is the code repository for [Linux Administration Cookbook](https://www.packtpub.com/virtualization-and-cloud/linux-administration-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781789342529 ), published by Packt.

**Insightful recipes to work with system administration tasks on Linux**

## What is this book about?
Linux is one of the most widely used operating systems among system administrators,and even modern application and server development is heavily reliant on the Linux platform.

This book covers the following exciting features:
Install and manage a Linux server, both locally and in the cloud 
Understand how to perform administration across all Linux distros 
Work through evolving concepts such as IaaS versus PaaS, containers, and automation 
Explore security and configuration best practices 
Troubleshoot your system if something goes wrong 
Discover and mitigate hardware issues, such as faulty memory and failing drives 

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/178934252X) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
# -*- mode: ruby -*-
# vi: set ft=ruby :

$provisionScript = <<-SCRIPT
sed -i 's#PasswordAuthentication no#PasswordAuthentication yes#g' /etc/ssh/sshd_config
systemctl restart sshd
SCRIPT
```

**Following is what you need for this book:**
If you are a system engineer or system administrator with basic experience of working with Linux, this book is for you.

With the following software and hardware list you can run all code files present in the book (Chapter 1-13).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-13 | Vagrant and VirtualBox, Around 8 GB of RAM and a 4 core CPU would be advisable | OS, Windows, Linux, macOS, or FreeBSD |


We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it]( https://www.packtpub.com/sites/default/files/downloads/9781789342529_ColorImages.pdf).

### Related products
* Hands-On Linux Administration on Azure [[Packt]](https://www.packtpub.com/virtualization-and-cloud/hands-linux-administration-azure?utm_source=github&utm_medium=repository&utm_campaign=9781789130966 ) [[Amazon]](https://www.amazon.com/dp/1789130964)

* PowerShell Core for Linux Administrators Cookbook [[Packt]](https://www.packtpub.com/networking-and-servers/powershell-core-linux-administrators-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781789137231 ) [[Amazon]](https://www.amazon.com/dp/1789137233)

## Get to Know the Author
**Adam K Dean**
has used Linux since 2005, when he rendered his first computer unbootable during an Ubuntu installation. Undeterred, a subsequent installation was successful, notwithstanding the odd graphical and Wi-Fi issues.

Between bouts of writing about himself in the third person, Adam now runs his own consultancy offering Linux expertise to a range of clients, though he hasn't forgotten his origins, and still occasionally renders computers unbootable.

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781789342529">https://packt.link/free-ebook/9781789342529 </a> </p>