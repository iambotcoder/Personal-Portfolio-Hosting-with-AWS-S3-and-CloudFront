# Personal Portfolio Hosting with AWS S3 and CloudFront

## Description

This project demonstrates how to host a personal portfolio website using Amazon S3 for static website hosting and Amazon CloudFront for content delivery and HTTPS support. The project leverages AWS cloud services to ensure the portfolio is globally accessible, secure, and fast.

## Features

- Hosted the personal portfolio website on Amazon S3 for global accessibility.
- Configured Amazon CloudFront for HTTPS support and edge caching.
- Integrated S3 with CloudFront to improve content delivery speed and security.

## Project Links

- **S3 Hosted**: [http://subodh--portfolio.com.s3-website-us-east-1.amazonaws.com/](http://subodh--portfolio.com.s3-website-us-east-1.amazonaws.com/)
- **CloudFront Hosted**: [https://d3hp686wnt8fep.cloudfront.net/](https://d3hp686wnt8fep.cloudfront.net/)

## AWS Setup

### 1. Setting up Amazon S3
- Create an S3 bucket and enable "Static website hosting" in the bucket properties.
- Upload all website files (HTML, CSS, JS, etc.) to the S3 bucket.
- Set the index document and error document to `index.html` and `error.html`, respectively.

### 2. Configuring Amazon CloudFront
- Create a CloudFront distribution with the S3 bucket as the origin.
- Enable HTTPS support by associating an SSL certificate with CloudFront.
- Configure caching and other settings for better performance.

## How to Use

1. Clone this repository:

```bash
git clone https://github.com/<your-username>/personal-portfolio-aws.git
```

2. Upload your website files to the S3 bucket.

3. Set up CloudFront to deliver your website securely.

4. Access the website via the provided CloudFront or S3 URL.



## Acknowledgements

- Amazon Web Services (AWS) for providing the necessary cloud infrastructure.
- CloudFront for enabling global content delivery.
