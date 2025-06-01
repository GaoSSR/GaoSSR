# Hi there, I'm GaoSSR 👋

![Profile Views](https://komarev.com/ghpvc/?username=GaoSSR&color=blueviolet)

## 🙋‍♂️ About Me

- 🎯 **Java开发工程师**，专注后端开发，热衷于高性能系统与架构优化
- 🛠️ 熟练掌握：Java、Spring Boot、MySQL、Redis、Git、Linux
- 💡 深入研究：高性能架构设计
- 🌱 正在学习：云原生、DevOps、系统架构设计
- 📝 热爱技术分享，持续输出原创文章与实战经验

## 📌 技术博客

- **CSDN博客专栏**：[GaoSSR-CSDN博客](https://blog.csdn.net/weixin_53622554?spm=1000.2115.3001.5343)
  - Java开发核心技术与源码剖析
  - Spring Boot、微服务实战
  - 持续更新，欢迎关注与交流！

## 🚀 代表项目

### [OnePro](https://github.com/GaoSSR/OnePro)
> **轻量级算法驱动优惠叠加器**  
> OnePro 专注于电商场景下的复杂优惠叠加问题，通过创新算法实现高效、灵活的最优解计算。适用于需要多种优惠（如满减、折扣、叠加券等）灵活组合、顺序依赖的业务场景。

#### 项目特色
- 📦 **高性能排列算法**：基于预计算与缓存，大幅提升复杂优惠组合的处理速度
- 🧩 **灵活的优惠叠加模型**：支持平行式与渐进式（依赖式）优惠顺序，适配各类电商促销需求
- 🧠 **抽象的计算引擎**：通过 Permutation、DiscountContext、Calculator 等核心组件，解耦业务与算法细节，便于扩展自定义优惠类型
- ⚡ **最优解自动选取**：自动枚举所有可能的优惠顺序，输出用户最省钱的优惠叠加结果
- 🛡️ **高效缓存机制**：Aₙ³级别缓存与预存排列结果，优化大规模订单和高并发环境下的计算性能

#### 技术亮点
- **Permutation<T extends GoodsItem>**  
  优化排列算法，高效缓存与唯一键生成，支持业务自定义调整性能参数
- **DiscountContext**  
  上下文对象，预计算+数组缓存，极大减少GC压力
- **PreCompute机制**  
  支持扩展预处理逻辑，灵活应对复杂商品与优惠关系
- **Calculator & AbstractCalculator**  
  分离具体优惠计算逻辑，支持多种优惠策略搭配与扩展
- **共享互斥协议(DiscountGroup)**  
  JSON协议灵活定义优惠共享与互斥关系，支持自动分组与高效过滤

#### 案例演示
项目内置完整的 Controller 示例，演示如何对商品集合应用优惠分组、自动计算全局最优解。

> 详细算法与源码解读请见：[OnePro 项目首页](https://github.com/GaoSSR/OnePro)  
> 欢迎 star、fork 与交流！

## 🛠️ 技术栈

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=GaoSSR&show_icons=true&theme=radical" alt="GaoSSR's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GaoSSR&layout=compact&theme=radical" alt="Top Langs" />
</p>

---

> **热爱编程，拥抱开源，持续成长！欢迎交流与合作~**
