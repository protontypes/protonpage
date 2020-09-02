---
date: 2020-09-02
title: "Launch of protontypes"
linkTitle: "Launch of protontypes"
description: "LibreSelery solves the Donation Distribution Problem in Free Software"
author: Tobias Augspurger, Johannes Karoff and Felix Dietze ([@protontypes](https://twitter.com/protontypes))
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"  
  params:
    byline: ""
---

Our digital world is powered by free and open source software. The innovation behind these projects is driven by the contributors and maintainers who invest their free time. Over 70% of all commercial source code today is based on free and open source software [[1]](https://www.synopsys.com/blogs/software-security/5-open-source-trends-2020-ossra/). All major technology companies build their core platform infrastructure on these free technologies [[2]](https://www.techrepublic.com/article/whats-really-behind-microsofts-love-of-open-source/). 

The following chart shows the distribution of funds among the larger projects in 2019 on the OpenCollective platform. It is obvious that some very popular projects, on which we all depend, receive relatively few donations. 

{{< imgproc featured Resize "700x" >}}
{{< /imgproc >}}

Today we will launch a large scale experiment to accelerate free, open and sustainable innovation. The idea of this experiment originated from a blog post of [Feross Aboukhadijeh](https://feross.org/funding-experiment-recap/) who realized that the profit of this development only goes to the big tech companies and larger software projects. Most software dependencies are not considered in the compensations. Donations only go to the maintainers, distribution to other contributors is arbitrary and often non-existent. Commercial companies worldwide tried to solve this problem with commercial solutions like GitHub Sponsor, OpenCollective, Tidelift or Patreon [[3]](https://www.oss.fund/all/). There is no free and open source solution to solve this problem yet. Another blog post suggests the creation of a donation pool for GitHub Actions but does not describe how the technical implemenation would look like. Colin McDonnell states: `there's currently no way to make a donation to the abstract concept of "open source software"` [[4]](https://vriad.com/essays/a-new-funding-model-for-open-source-software). From now on this is no longer valid:

<h3>LibreSelery</h3>

 _protontypes_ developed a new concept to remove the middleman in funding distribution with a free and open tool called [LibreSelery](https://github.com/protontypes/libreselery). The goal is to create a platform-independent tool to sustain continuous and autonomous payout to contributors in a transparent way. Anyone can immediately start collecting and distributing donations by integrating [LibreSelery](https://github.com/protontypes/libreselery) into any GitHub project. By using LibreSelery in your project, you will be able to include every person in your main project and dependency tree in the donations you collect. The tool runs in the continous integration pipeline of your project. All sources, log files and the transaction history is fully transparent for all GitHub users. We do not charge any fees since LibreSelery is not a platform. It is a piece of software. Only buying and selling cryptocurrency on the cryptomarket will create fees. For a simple integration we provide a GitHub template called [SeleryAction](https://github.com/protontypes/seleryaction) that offers user friendly integration without using the commandline. 

{{< imgproc concept Resize "800x" >}}
{{< /imgproc >}}

<h3>A Free Accelerator based on Free Funding</h3>
LibreSelery was developed in our open community called _protontypes_.
We support open source contributors in finding suitable [tools](https://github.com/protontypes/awesome-robotic-tooling), investors and contributors for your project. By using LibreSelery, it will be easier to find the right developers and supporters, because it ensures a transparent distribution of donations between all parties involved. 

If you want to start a new project, please post it in our forums. Our community will openly discuss the potential of your ideas, assist with online research and suggest possible fundraising opportunities.

<a href="https://discourse.protontypes.eu" style="display:inline-block; background: #495FFE; color: white; font-weight: bold; padding: 15px 25px; margin: 20px; border-radius: 5px;">Join the Forum</a>




