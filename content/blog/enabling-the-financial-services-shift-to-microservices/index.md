---
title: "服务网格加速金融科技向微服务转型"
date: 2018-08-08T22:12:16+08:00
draft: false
banner: "/img/blog/banners/0069RVTdgy1fu2nmrwb02j31ji15mnpf.jpg"
author: "Zach Jory"
authorlink: "https://aspenmesh.io"
translator: "甄中元"
translatorlink: "https://github.com/meua"
reviewer:  ["宋净超"]
reviewerlink:  ["https://jimmysong.io"]
originallink: "https://aspenmesh.io/2018/08/enabling-the-financial-services-shift-to-microservices/"
summary: "随着初创金融科技公司的竞争，以及客户期望的不断增长，成熟的金融服务公司必须改变他们提供产品和与客户开展业务的方式。在交付层面老系统很难满足这些要求，金融服务公司需要一套灵活、适应性强、可扩展性高、可靠且强大的软件架构。微服务使其成为可能，而服务网络正好满足了微服务大规模管理的需求。 "
tags: ["service mesh","fintech"]
categories: ["translation"]
keywords: ["service mesh","fintech"]
---

![](0069RVTdgy1fu2n6mulo0j30p70cdmzh.jpg)

金融服务公司通常都拥有沉重的历史包袱，当然对于想要进入这个行业的新秀来说也算是商业壁垒，因为他们很难突破低利润和严苛的监管规则。曾占主导地位的大型金融企业的市场份额正面临着比起小巧、灵活的小金融科技公司的蚕食。这些小科技公司技术嗅觉灵敏、专业、注重客户用户体验。为了保持良好的竞争优势，金融服务公司都计划将自己原有的繁杂的技术架构向更具适应性的方向转变。最近对金融机构的一项调查发现大约85％的人认为他们的核心技术过于僵化和缓慢。因此，预计在未来五年内约有80％的金融机构打算替换其核心银行系统架构。

金融新法则旨在解决新的数字支付问题。例如在欧洲的PSD2（支付服务指令法则），要求银行采用新的运营方式和交付方式。像PSD2这样的变化旨在将银行业带入开放的API共享经济，通过开放标准推动互操作性和集成。要成为数据开放、无缝集成、API共享的世界一流金融科技需要借助微服务的力量。

### 微服务为金融服务提供了三个关键优势

**增加安全性**

现代金融科技发展过程中给此前已建立的安全基础设施带来挑战。如数字钱包、智能机器人咨询服务和区块链等要求建立新的安全机制。恰恰微服务遵循这些要求正在构建基于最佳实践的独立身份识别服务。

**快速交付**

快速将新功能推向市场是金融科技在市场上赢得头筹的基石，微服务使得不同应用开发团队独立交付满足新客户需求的功能更易于实现，微服务也具有很强的扩展性去满足更多用户和交易。

**无缝集成**

金融科技在集成层面要求一组功能完备用于内部和外部不同服务间通信的服务接口。在大型单体应用中接口层由于改变难以管理而臭名昭著。而微服务利用隔离性、扩展性、弹性等众多特性使得接口更易于管理和更加安全。

### 服务网格使得繁杂的微服务管理易于实现

面对快速变化的客户、业务和监管要求，微服务帮助金融科技快速响应变化，但这不是轻而易举的，在转向微服务期间，公司需要承担增加的运营开销。而服务网格等技术恰可以帮助管理微服务。服务网格提供围绕可观测性、安全性、可控性一系列功能对于大规模管理微服务至关重要。

以前存在的解决方案（如DNS和配置管理）提供了例如服务发现等一些功能，但并没有提供快速重试、负载均衡、跟踪和运行状况监控的能力。管理微服务的老方法要求你在每次出现问题时拼凑出几种不同的解决方案，但是服务网格将它们打包起来使其更易于使用。虽然可以通过单个工具和流程完成服务网络管理的某些功能，但这是手动且耗时的。

随着初创金融科技公司的竞争，以及客户期望的不断增长，成熟的金融服务公司必须改变他们提供产品和与客户开展业务的方式。在交付层面老系统很难满足这些要求，金融服务公司需要一套灵活、适应性强、可扩展性高、可靠且强大的软件架构。微服务使其成为可能，而服务网络正好满足了微服务大规模管理的需求。 

>  文中提到的调研报告: https://www.pwc.com/jg/en/publications/pwc-global-fintech-report-17.3.17-final.pdf