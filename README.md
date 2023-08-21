# MongoDB database interface for VeighNa Framework

<p align="center">
  <img src ="https://vnpy.oss-cn-shanghai.aliyuncs.com/vnpy-logo.png"/>
</p>

<p align="center">
    <img src ="https://img.shields.io/badge/version-1.0.4-blueviolet.svg"/>
    <img src ="https://img.shields.io/badge/platform-windows|linux|macos-yellow.svg"/>
    <img src ="https://img.shields.io/badge/python-3.7|3.8|3.9|3.10-blue.svg" />
</p>

## Description

MongoDB database interface based on pymongo 4.1.1.

## Use

When using MongoDB in VeighNa, you need to fill in the following field information in the global configuration:

|Name|Meaning|Required|Example|
|---------|----|---|---|
|database.name|名称|是|mongodb|
|database.host|地址|是|localhost|
|database.port|端口|是|27017|
|database.database|实例|是|vnpy|
|database.user|用户名|否||
|database.password|密码|否||
