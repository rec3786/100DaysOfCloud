<br />

<p align="center">
    <a href="img/">
        <img src="ASG-creates-EC2s.png">
    </a>
    <h3 align="center">100 Projects in Cloud</h3>
<p align="center">
    Create an EC2 instance by using an Auto Scaling Group (ASG)
        <br />
        Lab 13
        <br/>
    </p>
</p>

<details open="open">
  <summary><h2 style="display: inline-block">Lab Details</h2></summary>
  <ol>
    <li><a href="#services-covered">Services covered</a></li>
    <li><a href="#lab-description">Lab description</a></li>
    <li><a href="#learning-objectives">Lab objectives</a></li>
    <li><a href="#lab-date">Lab date</a></li>
    <li><a href="#prerequisites">Prerequisites</a></li>    
    <li><a href="#lab-steps">Lab steps</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

## Services Covered

<img src="EC2.png"> Elastic Cloud Computing
<br> <img src="ASG.png"> Auto Scaling Group <br/>

## Lab Description

In this challenge, Amazon Elastic Compute Cloud (Amazon EC2) instances are configured and deployed using an Auto Scaling Group (ASG). First, a security group for a launch template is created. Next, an Auto Scaling Group is created. Finally, the Auto Scaling Group is tested. 

## Learning Objectives

⭐ Create an Auto Scaling Group that automatically creates EC2 instances.

## Lab date
   2024.01.23

## Prerequisites
*AWS Account or *DigitalCloud Training Challenge Lab subscription

## Lab Steps

    1. Create a security group that allows inbound HTTP traffic. 
<p align="center">
    <a href="img/">
        <img src="SecurityGroupProperties.png">
    </a>
</p>
<p align="center">
    <a href="img/">
        <img src="SecuirtyGroupCreated.png">
    </a>
</p>
    2. Create a launch template. Configure a launch template that will be used with EC2 Auto Scaling.
<p align="center">
    <a href="img/">
        <img src="LaunchTemplateProperties.png">
    </a>
</p>
<p align="center">
    <a href="img/">
        <img src="LaunchTemplateCreated.png">
    </a>
</p>
    3. Create an Auto Scaling Group. 
<p align="center">
    <a href="img/">
        <img src="ASGProperties.png">
    </a>
</p>
<p align="center">
    <a href="img/">
        <img src="ASGCreated.png">
    </a>
</p>
    4. Test the web server instances. Go to the public IPv4 DNS address of each of the new web server instances, and then verify that the custom home page is displayed. 
<p align="center">
    <a href="img/">
        <img src="EC2InstancesCreated.png">
    </a>
</p>
<p align="center">
    <a href="img/">
        <img src="EC2Instance1-Created.png">
    </a>
</p>
<p align="center">
    <a href="img/">
        <img src="EC2Instance2-Created.png">
    </a>
</p>

## Acknowlegements

⭐ [Digital Cloud Challenge Labs](https://digitalcloud.training/hands-on-challenge-labs/)
