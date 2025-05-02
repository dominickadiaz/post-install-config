<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>This tutorial provides a comprehensive guide to configuring osTicket after installation, ensuring the system is optimized for efficient ticket management and customer support. It covers essential steps such as setting up email integration, configuring user roles and permissions, defining ticket categories, and enabling automation features. By following this guide, users can tailor osTicket to meet their organization's specific needs, enhancing workflow efficiency and improving the overall help desk experience.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

1.) we are going to sign in under admin user and login to start creating OS ticket user and show how the ticketing system works 

![PIS1](https://github.com/user-attachments/assets/af80005e-3b72-4e4a-b07e-444a09bd9e54)
![PIS2](https://github.com/user-attachments/assets/99aadbee-d295-4e80-99f6-c91cd2a80519)
![PIS3](https://github.com/user-attachments/assets/c884704d-ad30-439f-b3ef-ff69b1637e7d)

</p>
<p>
2.) we are going to configure roles for grouping permissions

  ![PIS4](https://github.com/user-attachments/assets/cd15378e-bdad-425a-a7f3-a61023999566)

we are going to create a new role and name it Supreme Admin
![PIS5](https://github.com/user-attachments/assets/9a6bc99d-1e0c-4956-b67e-c1d6eaede2ab)

we are going to grant Supreme Admin, all access permissions
![PIS6](https://github.com/user-attachments/assets/80a8cbb8-be06-48b5-885e-8720061647f5)

3.) we will go on departments and create a new department called Sysadmins under a support role
![PIS7](https://github.com/user-attachments/assets/cc7d4afe-64ed-4286-940e-d18dee575d4f)

4.) next we will create a new team and label it Online banking 
![PIS8](https://github.com/user-attachments/assets/c9435a78-c830-4306-9b6f-12eaefc18e3e)

5.) we are going to go on User settings and make sure to uncheck unregistered users can create tickets
![PIS9](https://github.com/user-attachments/assets/11f47347-c916-4ca4-805f-4f32b67ab85a)

6.) now on the admin panel we are going to add two agents john and jane
![PIS13](https://github.com/user-attachments/assets/c598efb8-0346-4ecb-bfb0-3128a9a7f668)
![PIS12](https://github.com/user-attachments/assets/9b626697-a1d9-4c24-b9cb-0249c5971894)
![PIS11](https://github.com/user-attachments/assets/0644b520-a2a3-4af9-ad4e-c405c84aba59)
![PIS10](https://github.com/user-attachments/assets/a83303ea-9313-47c8-be8c-a890e070b9fa)

7.) we are going to go on the user panel and create a customer user, under the name of karen 
![PIS14](https://github.com/user-attachments/assets/90c8f3de-0a93-40d3-8a87-c322f1975228)

8.) now we are going to configure the SLA (Service Level Agreement) on the Admin panel 
![PIS17](https://github.com/user-attachments/assets/3707d549-497d-413d-acfc-fc39e132947c)
![PIS16](https://github.com/user-attachments/assets/45293323-9927-4a90-8240-77e043c628db)
![PIS15](https://github.com/user-attachments/assets/216c9ab0-1405-481f-b2bc-fafaf2dccabe)

9.) we now can create different help topics for the user customer to choose from so when submitted the topic onto the ticket, admins or employees can manage better solving troubleshooting

go to admin panel, then to manage and you will see help topics, then go to add new help topics and then i added these new help topics
![PIS 22](https://github.com/user-attachments/assets/ef9ca98b-4a6f-4e08-8272-4fef32a763db)
![PIS 21](https://github.com/user-attachments/assets/669b307e-8658-486c-88ff-ed85beb5481f)
![PIS 20](https://github.com/user-attachments/assets/519f46cc-f414-46d3-ac3c-fc81712046d4)
![PIS 19](https://github.com/user-attachments/assets/1a48d91a-0889-41a3-b987-77cb55813b14)
![PIS 18](https://github.com/user-attachments/assets/050a8925-4ffc-44ed-a270-4ab5ea18c557)


