## 前言

欢迎来到我们的基于前后端分离的外卖点餐系统项目！这是一个使用Java作为主要后端语言，结合Spring Boot框架，Vue.js、JavaScript以及CSS3等前端技术开发的毕业设计实战项目。项目旨在为用户提供一个便捷、高效、可定制化的在线订餐体验。

## 内容介绍

外卖点餐系统是一个集成了用户管理、商家管理、菜品管理、订单管理、配送管理等功能的综合性平台。用户可以通过系统浏览菜品、下单支付、追踪配送进度。商家可以管理自己的菜单、查看订单、处理订单。系统还提供了管理员功能，允许管理员进行系统设置、用户管理、商家管理等操作。

## 技术介绍

- **语言**：Java
- **使用框架**：Spring Boot
- **前端技术**：JS、Vue、CSS3
- **开发工具**：IDEA/Eclipse
- **数据库**：MySQL 5.7/8.0
- **数据库管理工具**：phpstudy/Navicat
- **JDK版本**：jdk1.8
- **Maven**：apache-maven 3.8.1-bin
- **前端环境**：Node.js 12/14/16

## 核心代码

```java
// 添加菜品接口
@PostMapping("/addDish")
public ResponseEntity<?> addDish(@RequestBody Dish dish) {
    dishService.addDish(dish);
    return ResponseEntity.ok().build();
}
```

上述代码展示了系统中添加菜品的核心后端逻辑。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/345372/19/492/85591/68bc770aFe26ecf97/29e91be8eb91ba68.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/323549/24/17201/10483/68bc76e7Ff3a2f7c8/d2d213e0187d8af1.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/322781/12/14720/12805/68bc76e8F39b23f88/72e1c82856ceff24.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/346175/8/507/16736/68bc76e8F0ea26f92/177a248ebe4c74ea.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/340204/16/7877/25348/68bc76e9F56adfdd1/877ce677e23d7a26.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/349228/18/499/25068/68bc76e9F88ccb472/72370b85c184d6c9.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/338874/13/7629/26155/68bc76e9F01e3e4c6/536edcc77a031081.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/345103/16/427/29476/68bc76eaFef058627/ac9ddd4fda9e5c33.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/345196/5/466/28468/68bc76eaFfb1d0542/d611c71552476b90.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/331235/18/10338/29218/68bc76ebF5cd9a3ee/d0fa8b6bd6270c98.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
