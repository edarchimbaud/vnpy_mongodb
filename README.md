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
|database.name|Name|Yes|mongodb|
|database.host|Address|Yes|localhost|
|database.port|Port|Yes|27017|
|database.database|Instance|Yes|vnpy|
|database.user|Username|No||
|database.password|Password|No||
