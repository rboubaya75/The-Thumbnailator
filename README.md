# **Brief: The Thumbnailator**

I have  undertaken this project in the framework of my professional training to become ** AZURE Cloud Developer ** at SIMPLON School in partnairship with Microsoft.

## Why the project was launched ? :

This project aims to help us better understand Azure functions, one of the most significant service in Azur

## What was launched ?
After discovering azure blob storage, we created a function that triggers an image thumbnailing whenever an image is uploaded within a blob container
For this purpose, I have created two blobs, which will contain pictures I upload and the images containers will stock a thumbnail of those uploaded ones.

****![](https://lh3.googleusercontent.com/xufreeBSAFjn5bWu-c1qKeU0tOZF_t16PjzBno3rm5i3xMs06l8N2OxVUXnL0JyXCPgFWoHK6acM7wpNMvv_GR_fKpCMYJ7_F0jQIRe4uae5THd5LkPzVon1bMM5MTF_9gTKnG9rDVY)

. For that purpose, I created an Azure function BlobTri which will do perfectly the job.

![](https://lh5.googleusercontent.com/Z1iY1Id5s7JcU-jMjma6iemIqKfHrKlROcsc9Gkl2VgF85VEzVRQdhp67xJI-XE8dqNdkoDPwX4qol3y-xoYDG70wMPyUd2Dp42t7ysX3cvVFYDs8uakrNbCc-L7wrBsfcuCcn-eono)

# A brief presentation of Azure functions
"Azure Functions is a cloud service available on-demand that provides all the continually-updated infrastructure and resources needed to run your applications. You focus on the pieces of code that matter most to you, and Functions handles the rest. Functions provides serverless compute for Azure. You can use Functions to build web APIs, respond to database changes, process IoT streams, manage message queues, and more."
As you can see below, we can add many functions that will be triggered if an event occurs. In our case, our function will be excecuted whenever a picture is uploaded in our specified container. 

![](https://lh6.googleusercontent.com/g_PmvcGPz5ImRbE68aADPnsS7KxKFN6s3uw6DtP9ISHsUH5q4D6HakP_8z1EjqsjGy8h6oQ05Q6znixrgc0KvCeo52s9K0Dxl8ZFgtkvx2x4HnQxvtkh31NDgTwEQ0oVRuMlAUGnaJk)

## Workflow of the function
This workflow gives a better understanding of the process
**![](https://lh5.googleusercontent.com/lMmYxYIeGcL30FX3jZEEjdpHnUBCZZ018vUpGkAmBKxF3CNsOm0hR8v3ImHvzMVx9Hq3oPROOgpw9XbvJg-S12_Y8q7caELRnkHB-Ezo9qDmUZgazXmXmNuWfXH3SlIH6b3etEQ5OSs)


# Project architecture in Kudu
"The advanced tools for App Service (also known as Kudu) provide access to advanced administrative features of your function app. From Kudu, you manage system information, app settings, environment variables, site extensions, HTTP headers, and server variables. You can also launch **Kudu** by browsing to the SCM endpoint for your function app, like `https://<myfunctionapp>.scm.azurewebsites.net/`"
For this project, I choose to manage my project directly in Kudu which has helped to focus in the code.
To install all the necessary requirements, place yourself at /wwwroot, where functions are stored, and launch the command line in the Debug Console. As we work in Node JS, we can launch an new project to install all the requirements.  **npm init** and **npm install**

  

install all requirements
![](https://lh5.googleusercontent.com/pVh-9_lZE3nVV5q_AMQEwe5KnoxLejb1Sutnvz29AWjE-wl-5OzKPNWWG4FAmPA_rWbz2it3stIDWSDE3f7rK_qXaQJLGeQeMx9njYsjNHSjNuUNe1dzxVpQ9_LL8FbXCuIE7VlxKt8)**


## The script in JavaScript and TypeScript 
Please refert to my files

## Difficulties and next steps
**Difficulties:**

**Next steps: email sender using SendGrid**

**![](https://lh6.googleusercontent.com/GV52rXipS_X8AyIMXMp1aaHoNGzT1qzg21llA0iiI2iue2xm5BxSN2jFaxHKc2tWbYoy-PKeNH6eN5zLKzkZV_9OsbPsBSy7lWGsfpeGESaIf5P8k-rGu96nWGycNMVDaLPmugSOL90)**
