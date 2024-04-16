---
layout: 
title: FOSS和非开源软件产品发布合规性指南（Checklist for Production Release）
description: 这部分页面主要是用于使用外部开源软件组件到自己的产品中，需要进行的详细检查。
nav_order: 
Auther:  Alfred Senior YANG
Email:   alfredsenioryang@foxmail.com
---

## FOSS和非开源软件产品发布合规性指南
**Checklist for Production Release** 
version 1.0

### 软件供应链安全
行业要求，以及特殊市场要求，有专门
市场的法律要求，以及这些市场对应的特殊领域的专门要求，比如汽车行业，医疗行业。
欧洲市场：GDPR

对于安全算法等，也要求必须明确声明，并及时报备？？？

### 原则和建议
最终发布产品，无论产品是否开源，都应该包含软件发布的版权声明。
- 当发售的纯私有代码的软件，软件产品中应该直接


### 法律法规要求

- [ ]  **1.1** LICENSE文件检查
        说明：按照绝大部分开源协议的要求，产品所使用的开源协议

### SPDX授权标识符的采用
**SPDX授权标识符： SPDX-License-Identifier**

根据SPDX组织推动建立的SPDX标志符标准（ISO/IEC 5962），在计划开源的软件中，或者基于开源软件增补的源码，都按照SPDX标准要求将其标识符嵌入源码头部。


FOSS源代码的头部应该
以及最新的SPDX的最新约定，SPDX标识符本身可能会发生变化，但这


[SPDX组织提供的SPDX授权标识符清单：在SPDX网站中](https://spdx.org/licenses/)



### LICENSE文件源
根据[GUN](https://www.gnu.org/)中对于各类开源软件license文件的[非正式翻译](https://www.gnu.org/licenses/translations.html#rules)的要求，本项目中汇总整理的各个开源软件license文件版本的中文版均由[GUN](https://www.gnu.org/)提供。

#### 中国开源软件先锋们的共线成果
结合中国自由软件和开源软件的发展及中国法律准则情况，本项目将接触的优秀中国开源领域和法学领域积极推动者们的成果呈现在此（目前仅罗列一项： [开放原子基金会](https://www.openatom.org/) ）。

建议在国内市场发布的开源软件和自由软件，优先采用中国开源软件业界的成果。
**这也是一种文化自信的表现，同时也是认可国内自由软件和开源软件先行者们的成果和贡献。**

**本项目推荐大家使用的中国开源法律和软件推动先驱的成果，来自于开放原子基金会旗下的 “[源译识](https://www.openatom.org/law/translate)” 的各位先行者们提供的 [翻译成果](https://atomgit.com/translation/Contransus/tree/master/%E8%AE%B8%E5%8F%AF%E8%AF%81%E7%BF%BB%E8%AF%91)** 。

### 常见开源软件授权协议解读
#### 强传染性的开源协议解读

##### GPL v3.0



![Commits](本文件夹内用于指示当前需要插入的附件的相对路径和文件全名（包括扩展名）)