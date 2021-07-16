---
title: "REACH 1.0"
date: 2019-05-12T12:14:34+06:00
image: "images/blog/post-3.jpg"
description: "This is meta description."
draft: false
---
Saakhi Charitable Society is a platform that aims to transform research into a collaborative community process with expertise sharing, open publishing, open peer reviews and public accountability. Saakhi aims to become the platform that is the backbone of this evolution. Community building and knowledge sharing are at the core of Saakhi’s objectives. Saakhi promotes the use of IPR’s in ways that promote community building and knowledge sharing. 

From the lessons learnt and inspired from Kerala Floods 2018, we wanted to develop a technology- based solution to bridge the gap between the demand and the available resources during the times of disaster relief and management. The **Resource Aggregation in Critical Hours(REACH)**, disaster management application has been developed with an aim to identify,locate,communicate, share and contribute all resources, including human power and materials. 

Presently we have developed the first stage of this application - REACH 1.0. This stage consists of five modules and currently can work in a hierarchical setup with various admin privileges as well as searches. 

### Hierarchical Setup
There will be a super admin under which there will be several regional admins which are divided on taluk bases. Under them there will be several area admins sorted on panchayat basis. The volunteers as well as the organizations will be under these area admins.

### Search Engine Module 
This module implements the four search features- search with name of service, name of service provider,service providers location,name of service providers organization. This will be helpful even if the user knows any one of the search parameters and is helpful in such situations.

### Access Control Module
This module deals with controlling access to authorized users only and credentials are validated.Since we are dealing with a very large amount of data which should be treated with privacy and security, this module will be helpful for data management. The data is stored in a secure database with Industry standard encryption.The login creations and deletion are done from the Backend

### Filter Selection Module
For the filtering of information and services based on the persons requirements, this module deals to filter the type of service provider and type of product from the inventory.

### Actor Control Module
For the efficient working of the system, it is important to manage who has control over the information in the system. This module is in control for creating user roles and permissions. This allows setting up groups like camps and teams. Also supports searching and setting of member profiles.

### Cloud Database Server
The most important part is the secure storage and retrieval of data. A Secure database is used to store all service provider information .Database encryption is implemented to protect data against threats
