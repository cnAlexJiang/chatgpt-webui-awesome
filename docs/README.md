# chat-gpt-full-stack
chatgpt 全栈解决方案  快速接入openai 
产品方案  运营策略  技术方案+实现

chatgpt full stack solution  

中文 - [English](./README_en.md)


## 开始更新

# SPA 
## vue2


## vue3


## react
 
# SSR
## next
[ChatGPT Next Web](https://github.com/Yidadaa/ChatGPT-Next-Web)

  一键免费部署你的私人 ChatGPT 网页应用。
<img src="https://raw.githubusercontent.com/Yidadaa/ChatGPT-Next-Web/main/docs/images/cover.png"/>


## astro

## php
[chatpht power by php](https://user-images.githubusercontent.com/5563148/224522389-f60e3047-c0e6-49cd-bee7-80feaf2c86a4.png)

PHP版调用OpenAI的API接口进行问答的Demo，代码已更新为调用最新的gpt-3.5-turbo模型。 采用Stream流模式通信，一边生成一边输出，响应速度超过官网
<img src="https://user-images.githubusercontent.com/5563148/224522389-f60e3047-c0e6-49cd-bee7-80feaf2c86a4.png"/>

# client 客户端

# weixin bot

## php方案
  [chatgpt-wechat-personal](https://github.com/dirk1983/chatgpt-wechat-personal)
  实现原理：
    腾讯服务器推送用户消息过来时，调用OpenAI的API接口，并将用户的问题和返回的结果存到日志文件中。
    在5秒内很可能收不到OpenAI返回的消息。没关系，直接让腾讯服务器发过来的请求响应超时。
    等腾讯第二次或第三次查询的时候，第一次请求调用OpenAI的结果也返回并写到文件中了，直接从文件中获取结果返回给用户。
<img src="https://user-images.githubusercontent.com/5563148/223959556-b9970db1-66fb-46fa-b3af-54d51c74cd5b.jpg"/>

  