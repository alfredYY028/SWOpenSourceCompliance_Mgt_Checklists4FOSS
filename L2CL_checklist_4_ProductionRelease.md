---
layout: 
title: 产品生产发布检查清单（Checklist for Production Release）
description: 这部分页面主要是用于使用外部开源软件组件到自己的产品中，需要进行的详细检查。
nav_order: 
Auther:  Alfred Senior YANG
Email:   alfredsenioryang@foxmail.com
---

## 最终产品发布检查清单 Checklist for Final Release 
version 1.0

[TOC]

### 原则和建议
最终发布产品，无论产品是否开源，都应该包含软件发布的版权声明。

**产品发布形态参考：** LICENSE文件检查
参考Github官网上以下几个公司的产品发布，参考以下同类半导体公司：
> [平头哥半导体（T-head-semi）在Github的仓库](https://github.com/T-head-Semi)
> [SiFive公司在Github的仓库](https://github.com/sifive)
> [瑞芯微RockChip在Github的仓库](https://github.com/rockchip-linux)

**产品发布形态：** 
对比上述厂商，以及竞品，我司在github上的发布，以下几个部分需要每个模块独立建立仓库。

> openSBI
> u-boot
> linux

其他，是否每个独立的模块通过这个方式独立的新建仓库？

### 各个独立开发交付的仓库
#### opensbi

**官方开源：** [opensbi](https://github.com/riscv-software-src/opensbi)
**源LICENSE种类：** The 2-Clause BSD License （SPDX short identifier: BSD-2-Clause)
**SPDX标识符：** SPDX-License-Identifier:    BSD-2-Clause

- [ ]  **license信息检测** LICENSE文件检查


  - [ ] 是否提供版权声明文件
  - [ ] 
    - [ ]  

#### 整体产品包的发布license检查

- [ ]  **产品发布形态：** LICENSE文件检查
        参考Github官网上以下几个公司的产品发布，参考以下同类半导体公司：
          [平头哥半导体（T-head-semi）在Github的仓库](https://github.com/T-head-Semi)
          [SiFive](https://github.com/sifive)
          [瑞芯微RockChip](https://github.com/rockchip-linux)

        建议新增需要发布的库按照以下两种license文件来发布：

  - [ ] 是否提供版权声明文件
  - [ ] 
    - [ ]  

 - [ ]  **1.2** 

	- [ ] Is the 
	- [ ] Does the 

 - [ ]  **1.3** 

**2.** 

- [ ] **2.1** 

- [ ] **2.2** 

- [ ] **2.3** 

- [ ] **2.4** 

- [ ] **2.5**  

- [ ] **2.6** 

- [ ] **2.7** 

### 最终发布的新内容
参考平头哥、SiFive的github仓库，未引用传染性开源代码的纯自研独立功能模块的软件，对外发布的时候建议使用以下两种license的授权：
> Apache 2.0
> MIT 

#### opensbi

**官方开源：** [opensbi](https://github.com/riscv-software-src/opensbi)
**源LICENSE种类：** The 2-Clause BSD License （SPDX short identifier: BSD-2-Clause)
**SPDX标识符：** SPDX-License-Identifier:    BSD-2-Clause

- [ ]  **license信息检测** LICENSE文件检查
        参考Github官网上以下几个公司的产品发布，参考以下同类半导体公司：
          [平头哥半导体（T-head-semi）在Github的仓库](https://github.com/T-head-Semi)
          [SiFive](https://github.com/sifive)
          [瑞芯微RockChip](https://github.com/rockchip-linux)

        建议新增需要发布的库按照以下两种license文件来发布：

  - [ ] 是否提供版权声明文件
  - [ ] 
    - [ ]  
