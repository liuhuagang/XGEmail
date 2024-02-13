# 简介  
Version:1.0.0  

&emsp;&emsp;It supports you to access Tencent's mailbox service in Unreal project and helps you send emails quickly. It is currently recommended to send only simple verification code.</br>
&emsp;&emsp;Plugin URL:  
&emsp;&emsp;&emsp;&emsp;[XGEmail(Wait for upload, currently unavailable)]();  
&emsp;&emsp;Sample Project URL:  
&emsp;&emsp;&emsp;&emsp;[XGEmail(Wait for upload, currently unavailable)]();  
&emsp;&emsp;English Description:  
&emsp;&emsp;&emsp;&emsp;[README](./README.md)  
&emsp;&emsp;Chinese Description:  
&emsp;&emsp;&emsp;&emsp;[中文说明书](./README_CN.md)  

Attention:  
1.The XGEmail plugin uses only the code provided by Unreal Engine 5 and has no other dependencies;  
2.The XGEmail plugin does not collect or send any information to the plugin author;  
3.Users must register Tencent's mailbox and open the smtp service, and correctly pass the mailbox information and right click information into the plugin interface.
# XGEmail 
## Blueprints  

![image](DocumentPictures/Product/G_Email_Send.png)  

## Flows

&emsp;&emsp;a.Obtain Tencent email account and authorization</br>
&emsp;&emsp;b.Call Email method</br>
&emsp;&emsp;c.Process the returned result</br>

## Access parameter
  

### Authorization parameter  

UserName:The user's email account</br>
AuthCode:User's email smtp service authorization code (This code is not the email password)</br>

### Mail parameter
  

FromName:The sender's email nickname</br>
FromEmail:Email account of the sender (recommended to be the same as the authorized user's email account)</br>
ToName:The recipient's email nickname</br>
ToEmail:The recipient's email account</br>
Subject:subject of an email</br>
Conent:Specific content of email</br>

## Example parameter  
UserName:709\*\*\*172@qq.com</br>
AuthCode:ko\*\*\*\*\*\*\*\*\*\*\*</br>
FromName:XiaoGang</br>
FromEmail:709\*\*\*172@qq.com</br>
ToName:Lucy</br>
ToMail:Lucy\*\*\*@163.com</br>
Subject:EmailTest</br>
Conent:Test123456</br>
## Contact Information    

Please contact me if you have any questions about [XGEmail(Wait for upload, currently unavailable)]().

QQ:
709777172  

Email:
709777172@qq.com  

bilibili:
[虚幻小刚](https://space.bilibili.com/8383085)  
