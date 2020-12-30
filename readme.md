# fuck12306-go

#### 介绍
引用
https://github.com/gzldc/12306
一个根据gzldc大佬做的12306抢票程序go版


#### 依赖库

- 验证码识别使用的是第三方

  ```
  http://littlebigluo.qicp.net:47720/
  ```

#### 功能特性
- [x] 自动打码
- [x] 自动滑块
- [x] 准点预售捡漏
- [x] 自动提交订单
- [x] 自动登录
- [x] 自动获取Cookie
- [x] 邮件通知
- [ ] 微信通知


#### 项目使用说明
- 修改配置文件

  ```
  配置文件格式是yaml不会的百度，邮箱地址先配置发件邮箱
  ```

- 使用方法

  ```
  1. go mod init go-12306
  2. go mod vendor
  3. go run main.go
  ```

#### 建议

```
登录12306，通过浏览器获取cookie信息
```
