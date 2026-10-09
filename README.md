# AWS Static Website Deployment Project

**Project Title:** Deployment of a Static Website Using Amazon S3, CloudFront, Route 53 and AWS Certificate Manager

**By Angel**

## Project Overview

This project demonstrates how to deploy a static website using Amazon S3 for website files, Amazon CloudFront for content delivery, Amazon Route 53 for DNS management, and AWS Certificate Manager (ACM) for SSL/TLS certificate management.

The website was deployed using the custom domain:

**https://angelaws.online**

## AWS Services Used

- **Amazon S3:** Stores the static website files.
- **Amazon CloudFront:** Distributes website content to visitors.
- **Amazon Route 53:** Manages the domain's DNS records and hosted zone.
- **AWS Certificate Manager (ACM):** Provides the SSL/TLS certificate used for HTTPS.
- **Namecheap:** Used to update the domain nameservers to Amazon Route 53.

## Project Implementation

### Step 1: Create an S3 Bucket

Created an Amazon S3 bucket and uploaded the static website files.

### Step 2: Configure a Lifecycle Rule

Configured an S3 lifecycle rule to manage object storage transitions and help optimize storage costs.

### Step 3: Configure S3 Access

Configured S3 public access settings and a bucket policy to allow public read access to website objects.

### Step 4: Configure Route 53

Created a public hosted zone for `angelaws.online`.

### Step 5: Update Domain Nameservers

Updated the domain nameservers in Namecheap to use the Amazon Route 53 nameservers.

### Step 6: Request an SSL/TLS Certificate

Requested an SSL/TLS certificate for `angelaws.online` using AWS Certificate Manager.

### Step 7: Create a CloudFront Distribution

Created and configured an Amazon CloudFront distribution for the website.

### Step 8: Configure DNS Records

Configured Amazon Route 53 DNS records to direct the domain to the CloudFront distribution.

### Step 9: Test the Website

Opened the deployed website in a browser and verified that it was accessible using the custom domain.

## Final Result

The static website was successfully deployed using Amazon S3, CloudFront, Route 53, and AWS Certificate Manager.

**Live Website:** https://angelaws.online

## Skills Demonstrated

- Amazon S3 static website hosting
- S3 lifecycle configuration
- S3 bucket policy configuration
- Amazon CloudFront distribution setup
- Route 53 hosted zones and DNS records
- Domain nameserver configuration
- SSL/TLS certificate management
- HTTPS website deployment and testing

## Project Documentation

The accompanying Word document contains screenshots showing the S3 bucket, lifecycle rule, bucket policy, Route 53 hosted zone, Namecheap nameservers, ACM certificate, CloudFront distribution, DNS records, and deployed website.

## Project Type

AWS Cloud Computing Training Project
