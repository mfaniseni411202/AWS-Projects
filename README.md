<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Host a Website on Amazon S3

**Project Link:** [View Project](https://nextwork.ai/projects/70e2d059-31ab-5f67-8c58-f5edbd451140)

**Author:** Banele Lethokuhle  
**Email:** banelethoku@gmail.com

---

![Image](https://nextwork.ai/relaxed_turquoise_kind_sea_otter/uploads/aws-host-a-website-on-s3_5d4474f9)

## Introducing Today's Project!

### Project overview

In this project, I will demonstrate the use of an S3 bucket I'm doing this project to learn how a website is stored in a bucket and the pictures and files are arranged to better enable how the website works

### Tools and concepts

Services I used were an S3 bucket, html file and a folder containing images and files  Key concepts I learnt include ACLs, S3 bucket usage and adavantages 

### Time, challenges, and wins

This project took me approximately 15 minutes The most challenging part was the bucket policy and recovering from the 403 error alone It was most rewarding to finish this project the fastest way people and the information that i acquired in this lesson will forever be embedded to my brain because i wish to make a difference in this industry that will be leading in a few years

## How I Set Up an S3 Bucket

### What I did in this step

In this step, I will Open Amazon S3,Create a storage space for your website files because i will be hosting a website inside an S3 bucket

### How long it took to create the bucket

Creating an S3 bucket took me less than 5 minutes which also consists the time to double check each input that made so that no errors can occur.

### Region selection

The Region I picked for my S3 bucket was Africa Cape Town because it is the one that is closest to me 

### Understanding bucket name uniqueness

S3 bucket names are globally unique! This means in all of AWS there wont be an S3 bucket that will be the same as mine 

![Image](https://nextwork.ai/relaxed_turquoise_kind_sea_otter/uploads/aws-host-a-website-on-s3_ba6d42ad)

## Upload Website Files to S3

### What I did in this step

In this step, I will Download an HTML file that sets up your website,Download a zip file of images for your website.
Upload both files into your S3 bucket. because it is time we upload these files into our S3 buckets so that we can host them.

### Files I uploaded

I uploaded two files to my S3 bucket they were an index html file and a folder containing images and files of the website

### How the files work together

Both files are necessary for this project as the html file is for the layout and the folder contains images that the user can be able to see and work with

![Image](https://nextwork.ai/relaxed_turquoise_kind_sea_otter/uploads/aws-host-a-website-on-s3_a265af88)

## Static Website Hosting on S3

### What I did in this step

In this step, I will configure the S3 bucket for static website hosting and visit my public website link because we need to test if the the files and layout we upload to the bucket are uploaded correctly without errors

### Understanding website hosting

Website hosting means making a website public on the internet

### How I enabled website hosting

To enable website hosting with my S3 bucket, I need to visit the properties of the S3 bucket which i saved my files in and configure static web hosting to be enabled 

### Access Control Lists (ACLs)

An ACL is a set of rules that decides who can get access to a resource. The ACLs are enabled so i know who can get access to the resource and do things with the objects

![Image](https://nextwork.ai/relaxed_turquoise_kind_sea_otter/uploads/aws-host-a-website-on-s3_c22c54c0)

## Bucket Endpoints

### Understanding bucket endpoint URLs

Once static website is enabled, S3 produces a bucket endpoint URL, which is a link that needs to display the files you have uploaded in a website format

### What I saw when I tested the endpoint

When I first visited the bucket endpoint URL, I saw an error 404 message The reason for this error was my ACLs are still configured to privatew

![Image](https://nextwork.ai/relaxed_turquoise_kind_sea_otter/uploads/aws-host-a-website-on-s3_22ce4daf)

## Success!

### What I did in this step

In this step, I will make website files in S3 publicly accessible because I need to see the website live on the internet

### How I resolved the 403 error

To resolve this 403 Forbidden error, I need to make the ACLs public through the actions button 

![Image](https://nextwork.ai/relaxed_turquoise_kind_sea_otter/uploads/aws-host-a-website-on-s3_5d4474f9)

## Bucket Policies

### What I did in this extension

In this project extension I'm about to set up a bucket policy to stop people from deleting my files, testing my policy I'm doing this so that my S3 buckets is more secure

### Understanding bucket policies

An alternative to ACLs are bucket policies, which are an advanced version of ACLs due to them using code.The benefit of using bucket policies is much more advanced protections of your resources that ACLs cant provide while ACLs are useful for simple access control 

### What my bucket policy does

My bucket policy prevent everyone from deleting a file in a bucket  I tested this by trying to delete the index.html file and saw an error mesage saying i have been denied to delete this file

---

*Built with [NextWork](https://nextwork.ai) - [View this project](https://nextwork.ai/projects/70e2d059-31ab-5f67-8c58-f5edbd451140)*
