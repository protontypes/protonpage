---
date: 2021-03-25
title: "Continuous Reforestation"
linkTitle: "Continuous Reforestation"
description: "Automated reforestation as a global scale carbon capture technology"
author: Tjark Doering, Alejandro Aristi, Jonathan Villiard, Tobias Augspurger, Carl Scheller ([@protontypes](https://twitter.com/protontypes)) ([@Digital Humani](https://twitter.com/Digital_Humani))
resources:
- src: "**.{png,jpg}"
  title: "Image #:counter"  
  params:
    byline: ""
---
## TL;DR

Although directly reducing greenhouse gas emissions is the best way to curb climate change in terms of cost and effectiveness, it will still be necessary to capture emissions already produced in the atmosphere for some decades to come. Reforestation is one of the most effective ways to do this as it is the only carbon sequestration technology that can be implemented cost-effectively and without generating large maintenance costs at the global scale. At the same time, it restores the original ecosystems that ensure biodiversity and provide other valuable natural resources such as water, soil and clean air.

With the [Continuous Reforestation GitHub Action](https://github.com/protontypes/Continuous-Reforestation) concept we demonstrate a simple way to automate the offsetting of greenhouse gas emissions throughout the life cycle of your products. It allows you to plant any desired number of trees based on various actions in your development workflow.

##  Automated Carbon Capture

Modern development processes such as *Continuous Integration* and *Continuous Deployment* frame the product usage and product development processes in a recurring, automated cycle. On the other hand, through a constant capture of field data, detailed information about the entire [life cycle impact](https://en.wikipedia.org/wiki/Life-cycle_assessment) can be generated. By combining these two apparently disconnected mechanisms, a direct and automated path to compensate for the estimated ecological footprint of many products becomes possible.

Continuous Reforestation is an important enabler in this context. A process that is otherwise used for quality assurance and lean development of digital products can also be used to reduce their ecological footprint. Moreover, it allows for a disclosure of the life cycle emissions and offsetting actions. Companies are now able to publicly demonstrate the sustainability of their products and how they offset their own impact on the environment. Customers and independent institutions have the opportunity to get a direct insight into the data. Greenwashing, one of the major problems on the way to an environmentaly sustainable economy, can thus be made much more difficult.

{{< imgproc devop Resize "500x" >}}
<div style="text-align: center; display: flex; align-items: center; flex-direction: column">
<a align="center" href="https://en.wikipedia.org/wiki/Continuous_integration">Continuous Integration - Modern software development method for the automation of development processes</a>
</div>
{{< /imgproc >}}

## Ecological Incentives

The usage of Continuous Reforestation in the development of open source products also creates ecological incentives in an straightforward way. The [OpenSustain.tech](https://opensustain.tech/) project is planting trees with every successful pull request. This has helped in the generation of new contributors which is a key aspect of the openness behind the project. A variety of actions can be rewarded in this way by planting trees:

* Reward pull request and first contributions to your project by planting trees accordingly.
* Motivate yourself and collegues to work on a project.
* Celebrating a new release, a specific milestone, or a closed issue.
* Penalize failed test by planting trees acordingly. 

## Reforestation as a Service and Digital Humani

Continuous Reforestation was developed using DigitalHumani's Reforestation as a Service (RaaS), an interface that simplifies the commissioning of tree planting to reforestation organizations via a single entrypoint. **[Digital Humani](https://digitalhumani.com/)** is a non-profit run by a band of dedicated volunteers from all over the globe with a mission to fight climate change by offering a free RaaS solution. They provide simple and easy to use Application Programming Interfaces (API) to help connect websites and mobile applications to trusted organisations that focus on ecosystems restoration. The RaaS solution is built by a team of IT experts with a high expertise in cloud technologies. The solution is highly secure, reliable, scalable, and an attempt to integrate reforestation as simply as possible into the development of products and processes. With their API, forest restoration can be easily automated, providing various benefits for the world by:

* Cleaning the air 
* Absorbing carbon 
* Increasing biodiversity 
* Providing food for local communities 
* Creating jobs for local communities 

{{< imgproc architecture Resize "900x" >}}
<div style="text-align: center; display: flex; align-items: center; flex-direction: column">
<a href="https://digitalhumani.com/">
The architecture of Reforestation as a Service from Digital Humani
</a>
</div>
{{< /imgproc >}}


## Forest restoration as a critical strategy to address climate change 

There are essentially two complementary ways to avoid global warming and a global disruption of Earth's environmental balance. The first way is to reduce the overall greenhouse gases emissions that result from human activities around the world. Frameworks such as the [Circular Economy](https://en.wikipedia.org/wiki/Circular_economy) provide the foundations to achieve this transformative shift of the production and consumption ways that took centuries to evolve into its present form. The second path is to capture the atmospheric CO2 excess that nature hasn't been able to absorb and thus, has been steadily increasing since the dawn of the 18th century and more drastically [since the 1950s](https://en.wikipedia.org/wiki/Keeling_Curve).

Within the second route, while large scale [carbon sequestration technologies](https://en.wikipedia.org/wiki/Carbon_capture_and_storage) show increasingly promising results, the overall environmental benefit (i.e. total lifecycle emissions being less than the captured CO2) is unclear. This means that there's currently no other known carbon drawdown solution that is quantitatively as large and effective in terms of carbon capture as tree and forest restoration. ([2018](https://science.sciencemag.org/content/365/6448/76), [2020](https://science.sciencemag.org/content/368/6494/eabc8905))

This becomes even more relevant when considering that there is still space to plant an additional one billion hectares of continuous forest without accounting for existing trees, urban, and agricultural areas. "Such a change has the potential to store an equivalent of 25% of the current atmospheric carbon pool." ([2018](https://science.sciencemag.org/content/365/6448/76)). However, with every passing year, the shifts in climate across diverse regions will reduce this potential area for tree coverage, stating the urgency to act now and promote the usage of nature-based solutions to counteract the effects of climate change.

{{< imgproc reforestationmap Resize "900x" >}}

<div style="text-align: center; display: flex; align-items: center; flex-direction: column">
<a href="https://science.sciencemag.org/content/365/6448/76">
The global tree restoration potential
</a>
</div>

{{< /imgproc >}}

## Going a step further

The Continuous Reforestation project has the potential to compensate greenhouse gases emissions within the working processes in an automated way. Hence, emissions caused by the design, development, and use of the products can be directly compensated. By disclosing the process steps, models, and reforestation status, the sustainability of a product can be transparently displayed to the customer. 

As a next step, with the help of the open source project [Scaphandre](https://github.com/hubblo-org/scaphandre), we will show how private individuals and companies can automatically compensate emissions from their servers and PCs.


## Conclusion
The creative integration of RaaS into products, workflows, and services offers a substantial and potentially large way to contribute to the reforestation efforts around the world. 

However, we should not forget that the avoidance of greenhouse gases and the prevention of deforestation should always come first. Further on, carbon capture technologies can help to compensate for emissions that can no longer be prevented.

## Further reading

* [Project Website of Continuous Reforestation](https://github.com/protontypes/continuous-reforestation)
* [Carbon Sequestration through Reforestation](https://semspub.epa.gov/work/HQ/176034.pdf)
* [Reforestation can sequester two petagrams of carbon in US topsoils in a century](https://www.pnas.org/content/pnas/115/11/2776.full.pdf)
* [The role of reforestation in carbon sequestration](https://www.fs.fed.us/nrs/pubs/jrnl/2018/nrs_2028_nave_002.pdf)
* [Young Forests Capture Carbon Quicker than Previously Thought](https://www.wri.org/blog/2020/09/carbon-sequestration-natural-forest-regrowth)
