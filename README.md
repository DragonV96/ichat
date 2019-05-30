# ichat-server
## 即时通讯demo后台服务端
- 聊天服务器采用Springboot + netty，快速开发支持高并发的聊天业务
- 图片服务器采用fastDFS，统一管理图片
- 数据库为mysql

## 实现功能：
- 用户的注册、登录与注销
- 用户离线推送消息
- 头像的上传与保存
- 修改昵称
- 好友申请与添加
- 心跳检测，断开长时间未活动的客户端，回收资源
