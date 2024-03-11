<h1>
  <span>肖霖畅</span>
  <span>
  </span>
  <ul>
    <img src="https://s11.ax1x.com/2023/12/26/pibEFGF.jpg" height="80">
  </ul>
  <ul>
    <li><span>年龄</span>24岁</li>
    <li><span>电话</span>158 1530 2312 / 191 6852 9238(备用)</li>
    <li><span>邮箱</span><a href="mailto:xiaolch3@mail2.sysu.edu.cn">xiaolch3@mail2.sysu.edu.cn</a></li>
    <li><span>个人主页</span><a href="https://xlcbingo1999.github.io/">https://xlcbingo1999.github.io/</a></li>
  </ul>
  
</h1>

## 教育经历
### 硕士 中山大学 计算机学院(软件学院) 计算机技术<span class="role">&nbsp;</span><span class="right">2022.09 - 2025.06</span>
### 本科 中山大学 计算机学院(软件学院) 软件工程<span class="role">&nbsp;</span><span class="right">2018.09 - 2022.06</span>


## 专业技能

- **编程语言**: 熟悉**C/C++**, **Golang**, Python, Swift/Objective-C; 了解Go的goroutine调度机制等底层原理
- **开发工具**: 了解**Kubernetes, Docker, Pytorch**等相关基础; 熟悉Linux的使用和维护; 熟悉Git等工具
- **专业技能比赛**: 2021年数学建模美赛 **一等奖Meritorious(约前10\%)** 等
<!-- - **外语能力**: CET-6, 阅读英文文档无障碍, 熟练撰写英文论文 -->

## 项目经历

### 基于异构超算的多元任务运行时系统(国家重点研发计划高性能计算专项)<span class="role">:&nbsp;项目开发</span><span class="right">2023.12 - 今</span>

- **项目背景**: 为解决应用多元化与超算环境异构化所带来的并行编程开发困难和运行效率不足的问题, 设计实现一套支持AI等任务和不同超算体系结构的任务级运行时系统
- **项目目标**: 设计通用的逻辑数据抽象与泛化的任务接口, 支持用户编写**屏蔽底层计算与存储资源**的并行应用, 提供**自定义任务调度接口**以满足不同多元任务的性能需求. **[技术栈: C++, CMake, 超算体系结构]**
- **承担工作**: 前期调研和原型设计; 将已有的任务级调度框架<a href="https://xlcbingo1999.github.io/assets/pdf/Legion_Stack_Intro.pdf">Legion</a>迁移部署到不同体系结构超算上; 设计特定并行模式的编程接口
- **阶段成果**: 完成系统设计; 完成Legion软件栈体系向<a href="https://www.nsccwx.cn/">神威太湖之光(自研体系结构)</a>和<a href="https://www.nscc-tj.cn/">天河三号(ARM)</a>的迁移 

---

### 基于Kubernetes的容器化AI云平台-DeepAI<span class="role">:&nbsp;后端开发&nbsp;<a href="https://xlcbingo1999.github.io/assets/pdf/DeepAI.pdf">架构链接</a></span><span class="right">2021.11 - 今</span>

- **项目简介**: 一站式AI任务平台, 用户可以利用平台提供的环境进行AI任务代码在线开发; 平台负责调度任务并分配训练资源, 并支持将训练模型部署为推理服务; 平台支持根据训练任务的价值和数据的隐私预算主动获取数据; 平台依据整体资源水位实现集群资源的弹性动态调整 **[技术栈: Golang, Python, Kubernetes]**
- **承担工作**: 系统后端实现和维护; 基于近似算法优化计算资源调度策略设计与实现; 基于在线算法优化隐私数据分配策略设计与实现
- **阶段成果**: 持续孵化科研论文, 未来仍会持续集成新的功能


## 实习经历

### 字节跳动 互娱研发-影像团队<span class="role">:&nbsp;客户端开发工程师</span><span class="right">2021.05 - 2021.11</span><br>

- **技术栈**: Swift, Objective-C
- **承担工作**: 搭建与维护<a href="https://m.ulikecam.com/">轻颜相机</a>内置的多媒体相册SDK(支持多媒体文件的增删, 修图修视频, 预览等功能)和上层UI逻辑; 参与搭建"拍摄-存草稿-修图-分享-回流"的社交链路全流程UI逻辑; 对Metal技术进行预研
- **商业成果**: 需求均按时上线, 协助推动轻颜在抖音上投稿影响力提升约10\%, 核心数据平稳, 无事故发生

## 研究经历<span class="role">&nbsp; 方向: 资源调度, 云计算, 隐私计算等&nbsp; <a href="https://xlcbingo1999.github.io/assets/pdf/Paper_System_Overview.pdf">概况链接</a></span>

### CRS: Cost-Aware Resource Scheduling for Deep Learning Jobs in the Elastic Cloud<span class="role">:&nbsp;共同一作</span>

- **理论贡献**: 将从云服务商处租用服务器来运行用户提交的任务的问题场景形式化, 主要目标为最小化租用成本; 形式化证明了本问题是NP-hard问题, 并提出一种基于贪心思想的<a href="https://xlcbingo1999.github.io/assets/pdf/approximation_algorithm.pdf">近似算法</a>, 理论证明了算法的近似比
- **系统贡献**: 基于本地集群搭建深度学习任务调度模拟系统, 利用Alibaba-PAI工作负载进行实验
- **成果**: 减小平均约45.1\%的集群部署成本; 整理形成论文, 正在审稿中, 模拟系统集成到DeepAI中

---

### Online Privacy Budget Allocation over Growing Datablocks for Model Training<span class="role">:&nbsp;第一作者</span>

- **理论贡献**: 数据分享平台为AI训练任务提供训练数据, <a href="https://www.amazonaws.cn/knowledge/what-is-differential-privacy/">差分隐私技术</a>为数据的隐私提供保证, 但每次数据的分享次数会有上限, 不合适的数据分配导致数据效用的降低; 本文提出了基于历史记录的<a href="https://xlcbingo1999.github.io/assets/pdf/online_algorithm.pdf">在线算法</a>, 理论证明了算法的竞争比; 本文进一步优化在线算法, 降低了分配策略的时间复杂度
- **系统贡献**: 基于本地集群搭建隐私数据分享模拟平台, 基于Alibaba-DP工作负载进行实验
- **成果**: 本文的算法在训练模型精度上带来了32.8\%的提升; 整理形成论文, 正在审稿中, 模拟系统集成到DeepAI中
