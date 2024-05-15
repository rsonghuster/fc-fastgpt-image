
> 注：当前项目为 Serverless Devs 应用，由于应用中会存在需要初始化才可运行的变量（例如应用部署地区、函数名等等），所以**不推荐**直接 Clone 本仓库到本地进行部署或直接复制 s.yaml 使用，**强烈推荐**通过 `s init ${模版名称}` 的方法或应用中心进行初始化，详情可参考[部署 & 体验](#部署--体验) 。

# fc-fastgpt-container 帮助文档
<p align="center" class="flex justify-center">
    <a href="https://www.serverless-devs.com" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=fc-fastgpt-container&type=packageType">
  </a>
  <a href="http://www.devsapp.cn/details.html?name=fc-fastgpt-container" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=fc-fastgpt-container&type=packageVersion">
  </a>
  <a href="http://www.devsapp.cn/details.html?name=fc-fastgpt-container" class="ml-1">
    <img src="http://editor.devsapp.cn/icon?package=fc-fastgpt-container&type=packageDownload">
  </a>
</p>

<description>

本案例将 FastGPT 快速创建并部署到阿里云函数计算 FC 。

</description>

<codeUrl>



</codeUrl>
<preview>



</preview>


## 前期准备

使用该项目，您需要有开通以下服务并拥有对应权限：

<service>



| 服务/业务 |  权限  | 相关文档 |
| --- |  --- | --- |
| 函数计算 |  AliyunFCFullAccess | [帮助文档](https://help.aliyun.com/product/2508973.html) [计费文档](https://help.aliyun.com/document_detail/2512928.html) |

</service>

<remark>



</remark>

<disclaimers>



</disclaimers>

## 部署 & 体验

<appcenter>
   
- :fire: 通过 [Serverless 应用中心](https://fcnext.console.aliyun.com/applications/create?template=fc-fastgpt-container) ，
  [![Deploy with Severless Devs](https://img.alicdn.com/imgextra/i1/O1CN01w5RFbX1v45s8TIXPz_!!6000000006118-55-tps-95-28.svg)](https://fcnext.console.aliyun.com/applications/create?template=fc-fastgpt-container) 该应用。
   
</appcenter>
<deploy>
    
- 通过 [Serverless Devs Cli](https://www.serverless-devs.com/serverless-devs/install) 进行部署：
  - [安装 Serverless Devs Cli 开发者工具](https://www.serverless-devs.com/serverless-devs/install) ，并进行[授权信息配置](https://docs.serverless-devs.com/fc/config) ；
  - 初始化项目：`s init fc-fastgpt-container -d fc-fastgpt-container`
  - 进入项目，并进行项目部署：`cd fc-fastgpt-container && s deploy -y`
   
</deploy>

## 案例介绍

<appdetail id="flushContent">

本案例是基于开源[FastGPT](https://github.com/labring/FastGPT)，简化 FastGPT 应用的初始化搭建过程，并且快速部署到阿里云函数计算FC。

FastGPT 是一个基于 LLM 大语言模型的知识库问答系统，提供开箱即用的数据处理、模型调用等能力。同时可以通过 Flow 可视化进行工作流编排，从而实现复杂的问答场景！

通过 Serverless 开发平台，您只需要几步，就可以体验 FastGPT，并享受 Serverless 架构带来的降本提效的技术红利。

</appdetail>

## 使用流程

<usedetail id="flushContent">

- 部署完成之后，您可以看到系统返回给您的案例地址
- 直接使用浏览器打开案例地址
- 使用账号名`root`, 密码值为您部署时候填写的 `DEFAULT_ROOT_PSW` 参数值（默认为 123456）
- 之后具体的使用流程请参考[FastGPT快速上手官方教程](https://doc.fastai.site/docs/course/quick-start/)


##  二次开发

请基于[FastGPT](https://github.com/labring/FastGPT)源码开发，然后将编译后的产物打包如该模版一样的zip包即可。

</usedetail>

## 注意事项

<matters id="flushContent">
</matters>


<devgroup>


## 开发者社区

您如果有关于错误的反馈或者未来的期待，您可以在 [Serverless Devs repo Issues](https://github.com/serverless-devs/serverless-devs/issues) 中进行反馈和交流。如果您想要加入我们的讨论组或者了解 FC 组件的最新动态，您可以通过以下渠道进行：

<p align="center">  

| <img src="https://serverless-article-picture.oss-cn-hangzhou.aliyuncs.com/1635407298906_20211028074819117230.png" width="130px" > | <img src="https://serverless-article-picture.oss-cn-hangzhou.aliyuncs.com/1635407044136_20211028074404326599.png" width="130px" > | <img src="https://serverless-article-picture.oss-cn-hangzhou.aliyuncs.com/1635407252200_20211028074732517533.png" width="130px" > |
| --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| <center>微信公众号：`serverless`</center>                                                                                         | <center>微信小助手：`xiaojiangwh`</center>                                                                                        | <center>钉钉交流群：`33947367`</center>                                                                                           |
</p>
</devgroup>
