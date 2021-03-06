# go-kuro 设计文档（中文版）

## 概述

`go-kuro` 是一个专门为 Go 开发的 metaprogramming 工具和框架，方便 Go 框架开发者编写出封装层次更高的代码，让业务开发者更加专注与业务逻辑而非各种细枝末节。

由于这个文档并非公开的设计文档，仅用于整理开发思路和对齐设计节奏，因此不会太过于在于文档组织的规范性，可能会比较跳跃。

具体设计思路详见[零碎的设计思路](thoughts.md)。

## 开发节奏

详见[路线图](roadmap.md)。

## 样例代码

用来表达具体思路的[样例代码](samples.md)。

## 周边信息

`kuro` 这个名字来源于日语「くろ」，意为「黑」，代表这个工具可以隐藏在幕后对代码进行处理和分析，使用者无需关注她的存在。

[Kuro（克洛伊）](https://zh.moegirl.org/%E5%85%8B%E6%B4%9B%E4%BC%8A%C2%B7%E5%86%AF%C2%B7%E7%88%B1%E5%9B%A0%E5%85%B9%E8%B4%9D%E4%BC%A6) 也是一个动漫角色，一定程度上 `go-kuro` 借用了这个角色的「投影（trace）」魔术的设定，项目中会使用相关的概念词汇作为起名字的依据。

## 使用许可

本文档按照 [CC-BY 4.0](http://creativecommons.org/licenses/by/4.0/) 进行授权。

作者信息：

    Kuro Devs <https://github.com/orgs/go-kuro/teams/kuro-devs>
