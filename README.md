# MarketPeak_Ecommerce Project

Welcome to My Cloud Computing capstone Project

## Table Of Contents
- Introduction
- Local environment Setup
- Navigation
- Challenges
- Acknowledgements

## Introduction

This Project entails development of an Ecommerce website and deployment on an AWS EC2 instance using Git version control. The project focuses on the efficient use of
Git version control system and Deployment using a server hosted in the cloud.

## Local Environmet Setup

- Create Local repository
- git init
- Obtain  and Prepare Ecommerce Website Template
- Stage and commit template to Git
- Push to remote repository
- Set up EC2 intance
- Clone repository to EC2 instance

## Navigation

- Install web server on EC2 (Apache HTTP Server(httpd))
    Apache http server is a widely used web server that serves html, css and javascript files over the internet
- Configure httpd for website
    it involves preparing the web directory by copying the html files into var/www/html
- Access website from Browser
    Use the public-Ip address of the EC2 instance to access the website

## Challenges

- Without installing git in the EC2 instance you can't carryout any git command. Use "sudo dnf install git"
- Without the right security group on the instance you can't access the website. Inorder to access the website HTTP port from anywhere should be activatedin the security inbound rules

## Acknowledgements

Thank you for riding with me to the end. We can now develop more websites and deploy it on AWS EC2 instance

