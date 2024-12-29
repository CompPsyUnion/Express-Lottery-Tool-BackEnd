# Simple Lottery Tool Backend
🌍 [中文](/README.md) | **English**

Built with Node.js + MongoDB, it supports running on Tencent Cloud's Serverless service.  
We pulled an all-nighter the day before we needed it, so the admin API doesn't have authentication yet, but we'll add it later.  
Please give us a Star～✨

## Related Projects
Frontend Github Project:  
The frontend is recommended to be built as an app using Electron or downloaded to devices using PWA, no deployment needed.  
Frontend Github Project👉[https://github.com/buduan/CPU-Lottery-Tool-FrontEnd/](https://github.com/buduan/CPU-Lottery-Tool-FrontEnd/)  
Admin Frontend Github Project👉[https://github.com/CompPsyUnion/GiftDrewAdminFE/](https://github.com/CompPsyUnion/GiftDrewAdminFE/)  
The admin frontend can be deployed to services like Tencent Cloud's static website hosting.  

## Installation Instructions  
First, you need to prepare a Node.js environment and MongoDB database management software on your server.

Then, create a new project directory and clone this repository into your project directory.

Modify the database connection settings (address, port, username, password) in app.js.

Run the following command in the terminal:
```
node app.js
```
We will package it into an executable file and adapt it for Cloudflare Workers in the future.

## API Documentation
Please visit👉[ApiFox](https://app.apifox.com/project/5639349) to view the API documentation.
