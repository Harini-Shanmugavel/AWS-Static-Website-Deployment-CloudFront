# AWS Static Website Deployment using Amazon S3 and CloudFront

## Project Overview

This project demonstrates how to deploy a static website using Amazon Web Services. 
The website files are hosted in an Amazon S3 bucket and delivered globally using AWS CloudFront Content Delivery Network (CDN). 

CloudFront caches the website content at edge locations to reduce latency and improve website performance for users across different geographic locations.

## Technologies Used

Amazon S3  
AWS CloudFront  
AWS Certificate Manager  
HTML  
CSS  
JavaScript

## Architecture

User Browser → CloudFront CDN → Amazon S3 Bucket (Static Website Files)

CloudFront acts as a content delivery network and caches files from the S3 bucket to deliver them faster to users.

## Implementation Steps

1. Created an Amazon S3 bucket to store static website files.
2. Uploaded HTML, CSS, JavaScript, and image files to the S3 bucket.
3. Enabled Static Website Hosting in the S3 bucket.
4. Configured bucket permissions to allow public read access.
5. Created a CloudFront distribution with the S3 bucket as the origin.
6. Configured the default root object as index.html.
7. Accessed the website using the CloudFront domain URL.

## Features

Global content delivery using CloudFront CDN  
Faster website loading using edge caching  
Scalable and highly available hosting  
Secure HTTPS delivery using SSL

## Output

The static website is accessible using the CloudFront distribution URL.

## Learning Outcomes

Understanding of Amazon S3 object storage  
Knowledge of CloudFront CDN architecture  
Experience deploying scalable static websites on AWS  
Understanding of caching and edge delivery mechanisms
