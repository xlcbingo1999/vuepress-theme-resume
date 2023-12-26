<h1>
  <span>肖霖畅</span>
  <span>
  </span>
  <ul>
    <img src="https://s11.ax1x.com/2023/12/26/pibEFGF.jpg" height="80">
  </ul>
  <ul>
    <li><span>年龄</span>24岁</li>
    <li><span>电话</span>158 1530 2312</li>
    <li><span>邮箱</span><a href="mailto:1220368815@qq.com">1220368815@qq.com</a></li>
    <li><span>Github</span><a href="https://github.com/xlcbingo1999">https://github.com/xlcbingo1999</a></li>
  </ul>
  
</h1>

## 教育经历
### 硕士 中山大学 计算机学院(软件学院) 计算机技术<span class="role">:&nbsp;</span><span class="right">2022.09 - 2025.06(预期)</span>
- **研究方向**: 资源调度, 云边计算, 隐私计算等; **GPA**: 4.48 / 5

### 本科 中山大学 计算机学院(软件学院) 软件工程<span class="role">:&nbsp;</span><span class="right">2018.09 - 2022.06</span>
- **GPA**: 3.842 / 5 (Rank: 26 / 158, 专业前17\%)


## 专业技能

- **编程语言**: 近期常用C/C++, Python; 有过Swift, Objective-C, Golang, Javascript等的相关开发经验
- **开发工具**: 熟悉Kubernetes, Pytorch, Git, Docker, LXD, LaTex, Pytorch; 熟悉Linux常见发行版的使用和维护
- **外语能力**: CET-6, 阅读英文文档无障碍, 熟练撰写英文论文

## 实习经历

### 字节跳动 互娱研发-影像团队-轻颜相机<span class="role">:&nbsp;客户端开发工程师</span><span class="right">2021.05 - 2021.11</span><br>

- **技术栈**: Swift, Objective-C
- **承担工作**: 搭建与维护移动端应用图片视频存储平台, 参与搭建轻颜相机"拍摄-存草稿-修图-分享-回流"的社交链路; 参与轻颜相机风格开放平台的开发和优化, 优化特效渲染逻辑, 优化资源的本地存储
- **商业成果**: 协助推动轻颜在抖音上投稿影响力提升约10\%, 项目平稳上线，覆盖约50万用户，核心数据平稳，无事故发生

## 项目经历

### 基于异构超算的多元任务运行时系统<span class="role">:&nbsp;项目开发负责人</span><span class="right">2023.10 - 今</span>

- **项目技术栈**: C/C++, Python, CMake, 超算体系结构
- **项目简介**: 国家重点研发计划高性能计算专项. 现有超算软件栈陈旧, 异构超算运行时系统无法快速适配. 本项目将对多样化应用和异构资源进行抽象建模, 支持上层编程框架向异构硬件映射; 分析计算图特征和应用数据依赖关系, 动态调整应用并行执行等策略; 最终本项目要在两种不同体系的新一代超算上部署
- **承担工作**: 前期调研和原型设计, 现有软件栈向新一代超算适配
- **项目阶段性成果**: 完成前期调研和原型设计; 完成CuNumeric, Legate, Legion, Realm软件栈体系向神威太湖之光的迁移 

---

### 基于Kubernetes的容器化AI云平台DeepAI<span class="role">:&nbsp;项目开发成员, 后端开发</span><span class="right">2021.11 - 今</span>

- **项目技术栈**: Golang, Kubernetes, Docker, MySQL, Kubeflow
- **项目简介**: 一站式AI模型训练系统, 平台目前可以提供代码编写, 隐私数据分配, 模型训练, 模型推理等功能. 用户可以利用该平台编写深度学习任务的代码, 支持从平台自动获取合适的数据, 用户提交的作业请求由系统调度和分配资源, 并支持将训练后的模型部署成推理服务供其他用户使用
- **承担工作**: 基于Kubeflow的分布式训练环境实现; 基于Kubernetes和近似算法优化计算资源调度策略; 基于差分隐私机制和在线算法优化隐私数据分配策略
- **项目阶段性成果**: 项目已经为相关企业提供服务, 持续孵化科研论文, 未来仍会持续集成新的功能


## 部分研究经历

### Online Privacy Budget Allocation over Growing Datablocks for Model Training<span class="role">:&nbsp;第一作者</span>

- **理论贡献**: 数据分享平台为持续到达的AI训练任务提供持续生成的训练数据服务, 利用差分隐私可以从数学理论上为数据的隐私提供保证, 但是每次数据的分享次数会有上限, 因此不合适的数据分配导致数据价值的降低; 本文提出了一种在线算法, 自动为AI训练任务选择合适的隐私数据, 并理论证明了算法的竞争比
- **系统贡献**: 基于本地集群搭建基于Kubernetes的隐私数据分享平台, 基于Alibaba-DP工作负载进行实验
- **成果**: 相比其他最先进的算法, 本文的算法在训练模型精度上带来了32.8\%的提升; 整理形成论文并投稿至CCF-A类会议, 正在审稿中

---

### CRS: Cost-Aware Resource Scheduling for Deep Learning Jobs in the Elastic Cloud<span class="role">:&nbsp;第二作者</span>

- **理论贡献**: 将从云服务商处租用服务器来运行用户提交的任务的问题场景形式化, 主要目标为最小化租用成本; 形式化证明了本问题是NP-hard问题, 并提出一种基于贪心思想的近似算法, 理论证明了算法的近似比
- **系统贡献**: 基于本地集群搭建基于Kubernetes的深度学习任务调度系统, 利用Alibaba-PAI工作负载进行实验
- **成果**: 在保持与其他算法作业完成时间接近的情况下, 减小平均约45.1\%的集群部署成本; 整理形成论文并投稿至CCF-A类期刊IEEE TPDS (审稿结果: minor revision)


