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
### 硕士 中山大学(985, 广州) 计算机学院(软件学院) 计算机技术<span class="role">&nbsp;</span><span class="right">2022.09 - 2025.06</span>
### 本科 中山大学(985, 广州) 计算机学院(软件学院) 软件工程<span class="role">&nbsp;</span><span class="right">2018.09 - 2022.06</span>


## 专业技能

- **编程语言**: 熟悉**Golang**, C/C++, Python, Swift/Objective-C。
- **开发工具**: 熟悉**Kubernetes, Docker**等相关基础; 熟悉Linux的使用和维护; 熟悉Git等工具; 熟悉操作系统, 计算机网络等基础。
- **荣誉**: 2021年数学建模美赛 **一等奖Meritorious(约前10\%)**, 中山大学研究生/本科生学业奖学金一等奖。
- **学生经历**: 中山大学计算机学院**学生会学术宣传部部长**, **班级团支书**等。
<!-- - **外语能力**: CET-6, 阅读英文文档无障碍, 熟练撰写英文论文 -->

## 实习经历

### 阿里巴巴 AI-Infra团队<span class="role">:&nbsp;基础平台开发</span><span class="right">2024.06 - 2024.09 </span>

- **技术栈**: Golang, Kubernetes
- **承担工作**: 参与 CNCF sandbox project <a href="https://github.com/kubedl-io/kubedl">KubeDL</a> 开发。 
  - 参与AI任务的编排组件开发, 管理Pods和自定义数据集等资源的创建到销毁的完整生命周期。
  - 参与AI任务容错机制建设, 负责任务热更新功能设计和开发, 可以避免用户重建AI训练任务, 降低用户修改任务到任务重启的时延。
  - 参与AI任务数据加速能力建设, 负责AI任务异步写Checkpoint功能(AI任务只写缓存集群, 异步完成缓存集群到OSS等云存储的同步, 用户无感)设计和开发, 降低AI任务写数据的时延。
- **成果**: 热更新功能降低约16\%-70\%的任务重启成本, 异步写功能降低约10\%-60\%的写数据时延。

---

### 字节跳动 互娱研发-影像团队<span class="role">:&nbsp;客户端开发</span><span class="right">2021.05 - 2021.11</span><br>

- **技术栈**: Swift, Objective-C
- **承担工作**: 搭建与维护<a href="https://m.ulikecam.com/">轻颜相机</a>内置的多媒体相册SDK(支持多媒体文件的增删, 修图修视频, 预览等功能)。
- **商业成果**: 均按时上线, 需求协助推动轻颜在抖音上投稿影响力提升约10\%, 核心数据平稳。

## 项目和科研经历<span class="role">&nbsp; 方向: 资源调度, 云计算, 隐私计算等&nbsp;</span>

### 基于Kubernetes的容器化隐私AI云平台-DeepAI<span class="role">:&nbsp;基础平台开发&nbsp;</span><span class="right">2021.11 - 2022.06 </span>

- **技术栈**: Golang, Kubernetes
- **项目简介**: 一站式AI任务平台, 用户可以利用平台提供的环境进行AI任务代码在线开发; 平台负责调度任务并分配训练资源, 并支持将训练模型部署为推理服务; 平台支持根据训练任务的价值和数据的隐私预算主动获取数据; 平台依据整体资源水位实现集群资源的弹性动态调整。
- **承担工作**: 系统后端实现和维护; 基于近似算法优化计算资源调度策略设计与实现; 基于在线算法优化隐私数据分配策略设计与实现。
- **成果**: 计算资源调度算法减小平均约45.1\%的集群部署成本, 考虑隐私预算后的训练模型精度上带来了32.8\%的提升, 并持续孵化科研论文:
  - CRS: Cost-Aware Resource Scheduling for Deep Learning Jobs in the Elastic Cloud, 以**第一作者**身份投稿, 被CCF'A期刊TMC接收
  - Online Privacy Budget Allocation over Growing Datablocks for Model Training, 以**第一作者**身份投稿, 被CCF'A期刊TSC接收

---

### 基于异构超算的多元任务运行时系统<span class="role">:&nbsp;项目开发</span><span class="right">2023.12 - 今</span>

- **技术栈**: C++, CMake, 超算体系结构
- **项目背景**: 为解决应用多元化与超算环境异构化所带来的并行编程开发困难和运行效率不足的问题, 设计实现一套支持AI等任务和不同超算体系结构的任务级运行时系统。
- **项目目标**: 设计通用的逻辑数据抽象与泛化的任务接口, 支持用户编写**屏蔽底层计算与存储资源**的并行应用, 提供**自定义任务调度接口**以满足不同多元任务的性能需求。
- **承担工作**: 前期调研和原型设计; 将已有的任务级调度框架<a href="https://xlcbingo1999.github.io/assets/pdf/Legion_Stack_Intro.pdf">Legion</a>迁移部署到不同体系结构超算上; 设计特定并行模式的编程接口。
- **阶段成果**: 完成系统设计; 完成Legion软件栈体系向<a href="https://www.nsccwx.cn/">神威太湖之光(自研体系结构)</a>和<a href="https://www.nscc-tj.cn/">天河三号(ARM)</a>的迁移。
