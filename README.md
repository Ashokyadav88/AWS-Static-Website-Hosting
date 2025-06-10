# AWS Static Website Hosting

## Project Overview
Host a static portfolio website using AWS S3, Route53, and CloudFront.

## Features
- HTML/CSS-based static site
- Hosted on S3 with public access and HTTPS via CloudFront
- Custom domain mapping with Route53

## Setup Instructions
1. Create an S3 bucket named `your-domain.com`
2. Upload your static site files (index.html, etc.)
3. Enable static website hosting in bucket properties
4. Configure a custom domain in Route53 and set up alias records
5. Create a CloudFront distribution and connect it to your S3 bucket
6. Attach SSL certificate via ACM

## Files Included
- index.html (basic landing page)
- S3 bucket policy template
- CloudFront setup guide

