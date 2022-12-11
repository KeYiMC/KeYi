<img src="https://user-images.githubusercontent.com/83630775/196994084-2c53ac23-f4be-4b90-b6fc-1b0ba65ea1b8.png" alt="KeYi's logo" align="right" width="400">
<div align="left">
  <h4>Also available in: <a href="https://github.com/KeYiMC/KeYi/blob/develop/1.19.3/README_ZH.md">中文</a></h4>
  <h1>KeYi</h1>
  <h3>⚡ The next generation Minecraft server software aims to the balance of performance and stability.</h3>
  <h5>This project is still under heavy development, use it at your own risk!</h5>
  <i><h5>KeYi, is the Chinese word "可以", means some thing is very OK!</h5></i>

[![Discord](https://img.shields.io/discord/1030133252134027304?color=%235865f2&label=Discord&logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/Sm2NsY5dpV)
[![Tencent QQ](https://img.shields.io/badge/Tencent%23QQ-%2312B7F5?style=for-the-badge&logo=tencentqq&logoColor=white)](https://jq.qq.com/?_wv=1027&k=tNDYZa7z)
</div>

# Why another fork?

The answer is quite simple.

The existing forks doesn't meet up what our requires, so we made up a small team and created this fork.

# Roadmap

As you can see, this fork is designed to be stable and well supported Purpur fork, but also gain some performance improvements. 

The improvements of the API is also being valued, so we will try our best to work on it.

# Versioning

| Version | Support Status                  | Download                                                     |
| ------- | ------------------------------- | ------------------------------------------------------------ |
| 1.18.2  | ❌                               | Not exists.                                                  |
| 1.19.2  | ✔️ LTS version, will be end at 2023-2-1. | [main](https://github.com/KeYiMC/KeYi/releases/tag/main-1.19.2), [develop](https://github.com/KeYiMC/KeYi/releases/tag/develop-1.19.2). |
| 1.19.3  | ✔️                               | [main](https://github.com/KeYiMC/KeYi/releases/tag/main-1.19.3), [develop](https://github.com/KeYiMC/KeYi/releases/tag/develop-1.19.3). |

# API

### Maven

#### Adding repository

```xml
<repository>
    <id>keyi</id>
    <url>https://maven.pkg.github.com/KeYiMC/KeYi</url>
</repository>
```

#### Adding dependency

```xml
<dependency>
    <groupId>cc.keyimc.keyi</groupId>
    <artifactId>keyi-api</artifactId>
    <version>1.19.3-R0.1-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
```

### Gradle

#### Adding repository

```groovy
repositories {
    maven("https://maven.pkg.github.com/KeYiMC/KeYi")
}
```

#### Adding dependency

```groovy
dependencies {
    compileOnly("cc.keyimc.keyi:keyi-api:1.19.3-R0.1-SNAPSHOT")
}
```

# Contributing

Unfortunately, the rules of our community haven't been finished yet. 

So at this time, if you want to contribute, you need to talk with us on Discord or Tencent QQ.
