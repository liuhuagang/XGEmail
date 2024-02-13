# Brief  

Version:1.0.0  

&emsp;&emsp;XGEmail是一款虚幻引擎5插件,它支持你在虚幻项目中访问腾讯的邮箱服务,帮助你快捷地发送邮件.目前推荐只用来发送简单的验证码.  
&emsp;&emsp;虚幻商城插件地址:  
&emsp;&emsp;&emsp;&emsp;[XGEmail(等待通过后上传,目前不可用)]();  
&emsp;&emsp;示例项目下载:  
&emsp;&emsp;&emsp;&emsp;[XGEmailDemo(等待通过后上传,目前不可用)]();  
&emsp;&emsp;英文说明:  
&emsp;&emsp;&emsp;&emsp;[README](./README.md)  
&emsp;&emsp;中文说明:  
&emsp;&emsp;&emsp;&emsp;[中文说明书](./README_CN.md)  

注意:  
1.XGEmail插件仅使用了虚幻引擎5提供的代码,不含其他依赖;  
2.XGEmail插件不会收集和发送任何信息给插件作者;
3.用户必须自行注册腾讯的邮箱并开启smtp服务,并将邮箱信息和右键信息正确传入插件接口.
# XGEmail  
## 蓝图速览  

![image](DocumentPictures/Product/G_Email_Send.png)  

## 使用流程

&emsp;&emsp;a.获取腾讯邮箱账户及授权</br>
&emsp;&emsp;b.调用插件接口</br>
&emsp;&emsp;c.处理返回结果</br>

## 访问参数  

### 授权参数  

UserName:用户的邮箱账户</br>
AuthCode:用户的邮箱smtp服务授权码(该码不是邮箱密码)</br>

### 邮件参数  

FromName:发件人的邮箱昵称</br>
FromEmail:发件人的邮箱账号(建议与授权的用户邮箱账号保持一致)</br>
ToName:收件人的邮箱昵称</br>
ToEmail:收件人的邮箱账号</br>
Subject:邮件主题</br>
Conent:邮件具体内容</br>

## 示例参数  
UserName:709\*\*\*172@qq.com</br>
AuthCode:ko\*\*\*\*\*\*\*\*\*\*\*</br>
FromName:XiaoGang</br>
FromEmail:709\*\*\*172@qq.com</br>
ToName:Lucy</br>
ToMail:Lucy\*\*\*@163.com</br>
Subject:EmailTest</br>
Conent:Test123456</br>


# 联系方式  

如果有任何[XGEmail(等待通过后上传,目前不可用)]()插件产品问题,请联系我.  

QQ:
709777172  

Email:
709777172@qq.com  

bilibili:
[虚幻小刚](https://space.bilibili.com/8383085)  