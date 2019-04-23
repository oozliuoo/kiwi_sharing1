## Recap

- ~参会成员介绍~
- ~项目环境搭建及项目结构~
    - ~项目依赖讲解~
- ~项目本地运行及部署~
- 目前开发流程中不完善的地方
- Q&A


## 先有请玉成发言


### 玉成
- 代码复用性太差
- 都是些复制黏贴的活
- 说是前端，但干的不是前端的活
	- 前端的页面完全不是我来决定的，都要跟原生层沟通
	- 从布局到功能都是
	- 感觉受限很大，很郁闷


- 流程上很不灵活
	- 底层也比较依赖原生层
	- 组件之间的通讯
- 多机的场景让开发变得复杂
- envoy 的文档缺失
- 新的功能建议产品跟原生层先沟通


- 没有一个项目脚手架，开始新项目全靠复制黏贴 <!-- .element: class="fragment" data-fragment-index="1" -->
- package 中重复代码过多及冗余 <!-- .element: class="fragment" data-fragment-index="2" -->
- 底层项目重构的版本还没能推进，目前靠锁死版本维持生活 <!-- .element: class="fragment" data-fragment-index="3" -->
- 底层框架代码可维护性低 <!-- .element: class="fragment" data-fragment-index="4" -->
- 缺少持续集成和测试 <!-- .element: class="fragment" data-fragment-index="5" -->
- 缺少持续、自动追踪不同 package 部署情况的工具，全靠好记性和烂笔头 <!-- .element: class="fragment" data-fragment-index="6" -->
- 缺少文档 <!-- .element: class="fragment" data-fragment-index="7" -->