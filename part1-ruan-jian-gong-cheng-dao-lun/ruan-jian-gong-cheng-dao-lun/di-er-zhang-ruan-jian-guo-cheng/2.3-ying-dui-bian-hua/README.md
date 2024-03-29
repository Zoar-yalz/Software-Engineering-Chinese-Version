# 2.3 应对变化

在大型软件项目中，变化不可避免。系统需求会因为业务应对外部压力、竞争和管理优先级改变而变化。因此无论使用什么软件过程模型，它都必须能在开发时适应变化。

变化会增加软件开发的成本，因为它经常意味着已经完成工作需要重做。这也叫返工。比如说，如果系统内需求关系已经被分析过之后出现了新的需求，需求分析的部分或是全部都需要重新开始。为了实现新的需求，甚至可能需要重新设计系统，修改部分已完成的程序，然后对系统重新测试。

可以采用两种相关方法来减少返工的费用：

1. 改变预期：需要给软件过程添加可以在大型返工前预测可能的改变的活动。比如说，可以开发一个原型系统来给顾客展示一些系统的核心特性。他们可以使用原型进行测试，在软件开发费用提升之前精炼需求。
2. 改变宽容度：将过程和软件设计为很容易对系统做出改变。这一般包括一些形式的增量开发。新提出的改变可以在还没开发完的增量中实现。如果这不可行的话，也只需要更改一个增量（系统的一小部分）来适配这个改变。

在这章中，我讨论了两个面对变化，更改系统需求的方式：

1. 系统原型（System prototyping）：快速开发出一个系统版本或是系统一部分来确认需求和设计决定的可行性。这个方法会改变用户的期望，因为它允许用户在交付系统前进行使用，对需求进行优化。因此交付后更改需求的想法也会变少。
2. 增量交付（Incremental delivery）每个系统增量会交付给用户用于实验和评价。这同时帮助了避免修改和修改容忍度。它杜绝了对整个需求不成熟的修改申请，并且允许在后面的增量中使用较低的成本添加功能。

重构的概念，即改进程序的结构和组织，也是一个重要的增加修改容忍度的办法。我会在第三章（敏捷方法）中介绍它。
