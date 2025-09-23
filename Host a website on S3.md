<h1>Host a website on S3</h1>

<h2>Description</h2>
In this project, I went back through on my own free teir account and set up a  S3 Bucket. I'm doing this project to learn more about AWS and also how to document my projects on github. 
<br />

<h2>Environments Used </h2>

- <b>AWS</b> 

<h2>walk-through:</h2>

<p align="center">
Firstly I set the AWS region on my account to Sydney as it is the closest AZ to where I was located. Next, I created an S3 Bucket and created space for files. I named the bucket and learnt that S3 bucket names are globally unique! This means once I create mine nobody else can have the same Bucket name.<br/>
<br />
<img src="https://i.imgur.com/NU1t82i.png"  height="80%" width="80%" 
<br />
<br />
Creating an S3 bucket took me a few minutes. The AWS console made it easy. I learnt about Access control list's (ACL). They are a set of rules that enable you to decide who has access to a resource. I chose to enable ACL's so that I could control who has access and what they can do with the resources.  <br/>
<br />
<br />
I made an HTML file that will set up my website, I did this by opening notepad and using html. I also selected an image for my website and then uploaded both files into my S3 Bucket. This showed that the Bucket is working how it should.
<br />
 <br />
<img src="https://i.imgur.com/Nb4iMGi.png"  height="80%" width="80%" 
<br />
<br />
I then went on to configure a static website domain. This too was done through the console. Website hosting means that AWS is providing the service and hosting my website in the cloud. To enable website hosting with my S3 bucket, I enabled static website hosting and Used to my index.html to create a webpage. <br/>
<br />
 <img src="https://i.imgur.com/26Fx7du.png"  height="80%" width="80%" 
<br />
<br />
 Once the static website is enabled, S3 produces a bucket endpoint URL, which is a way for users to visit my S3 Bucket as a website. 
<br />
<img src="https://i.imgur.com/2JV5LF4.png"  height="80%" width="80%" 
<br />
<br />
When I first visited the bucket endpoint URL. I saw a 403 Forbidden error. The reason for this error was that the content in my S3 Bucket was still set to private.To resolve this 403 Forbidden error, I made the objects in my bucket public by setting new ACL permissions. once this was completed I could visit the website by using the link.<br/>
<img src="https://i.imgur.com/IKE9hH2.png"  height="80%" width="80%" 
<br />
<br />
 From here I deleted all the content from the bucket and Then deleted the Bucket.
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
