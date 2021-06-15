# Learning_Journal
Learning_Journal_Weekly_Insights
Week_1 

Learning Activites
- Using HTML and CSS effectively to update content to my static website.
- Creating an AWS free tier account.
- Learning to use AWS to host a static website.

I learnt to host a basic website using html and css on the AWS free tier cloud services. The first step was to create a website for a ficticious competition caller Scelra using html to structure the site and CSS to style my website. Once my website was created I had hosted it on a AWS instance. 

I learnt that AWS allows us to create a custom EC2 (Elastic compute 2) instance. The instance that I selected was a computer that uses Amaxon Linux and this instance was avaliable for use with a the tier account for a year. 

This server uses an elastic model and we only pay what we use. 

I learnt to use AWS by watching a few youtube videos were: 
Amazon free tier account.
YouTube videos:
How to Host Your Website on AWS EC2 Instance - https://www.youtube.com/watch?v=dhRwKPrum44&t=4s and Joomla! Cloud hosting with Amazon EC2 Video Tutorial Part 1 - https://www.youtube.com/watch?v=Uo-JGmutlr0

To host a website we need to use the Apache HTTP Server, colloquially called Apache, is a free and open-source cross-platform web server software which is installed on the Amazon Linux instance. Next, I learnt to create a storage server called S3 bucket. This is were my website files would be uploaded.  

Finally, I had to create an IAM (Identity Access Manangement) role and give full access to my S3 storage server, I had to do this since I as the user needed to access this remotely using SSH and needed full access. Using putty application, I managed to telnet via SSH into my Amazon Linux Instance where I had to change directory to var/www/html/ and this will syncronize all our files from my S3 bucket to the var/www/html directory.

Challenges - I was not able to successful run this command and did more research and was had eventually managed to find a different method on installing Linux using Amazon Lightsail. This installed Joomla and helped me create a public IP address which I can use to access my site. 

The IP address to my site is: 54.206.204.31
