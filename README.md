# citrix.github.io
citrix.project

名称：跨云认证
目标：实现一个认证服务，用以认证来自不同云平台的用户及用户组
用户场景：用户已在Amazon Web Service 或 Google Cloud Platform上注册了相关信息，并部署了资源。此时，用户希望能够运行Azure上的Citrix虚拟云桌面。通过此认证服务，用户无需在Azure上再行注册，即可开始使用。

注意：可使用任意编程语言实现该认证服务。
一个可供参考的例子是identityserver（https://github.com/IdentityServer/IdentityServer4），可基于此实现对AWS/GCP的认证接口。![image](https://user-images.githubusercontent.com/33984530/125441503-00f9be22-fafc-46f5-ab73-3f4b9e9d907d.png)
