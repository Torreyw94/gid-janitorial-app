# GID Janitorial Management Services

Welcome to the GID Janitorial Management Services website. This project showcases the top moments of our services and provides a way for users to contact us for various cleaning services.

## Table of Contents

- [Introduction](#introduction)
- [Services](#services)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)

## Introduction

GID Janitorial Management Services offers a range of cleaning services, including commercial business cleanings, commercial under-construction cleanings, and residential cleanings (Airbnb included). Our website allows users to view our top moments and contact us for services.

## Services

### Commercial Business Cleanings

We provide comprehensive cleaning services for commercial businesses to ensure a clean and professional environment.

### Commercial - Under Construction Cleanings

Our team specializes in cleaning under-construction sites to maintain safety and cleanliness during the construction process.

### Residential Cleanings (Airbnb Included)

We offer residential cleaning services, including Airbnb turnovers, to keep homes and rental properties spotless.

## Technologies Used

- **HTML**: For structuring the web pages.
- **CSS**: For styling the web pages.
- **JavaScript**: For adding interactivity to the web pages.
- **AWS Lambda**: For serverless backend processing.
- **AWS API Gateway**: For creating and managing APIs.
- **AWS DynamoDB**: For storing lead information.
- **AWS SES**: For sending email notifications.
- **Terraform**: For infrastructure as code to manage AWS resources.

## How to Run

To view the website locally, you can use Live Server in Visual Studio Code:

1. Open the project in Visual Studio Code.
2. Right-click on `index.html` and select "Open with Live Server".
3. The website will open in your default web browser.

Alternatively, you can deploy the website to an S3 bucket for static website hosting:

1. Create an S3 bucket in the AWS Management Console.
2. Enable static website hosting on the bucket.
3. Upload the `index.html`, `styles.css`, and `script.js` files to the bucket.
4. Access the website using the S3 bucket URL.
