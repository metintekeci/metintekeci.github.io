---
layout: post
title: Reflections on financial modeling
subtitle: ...experience from corporate world.
tags: [financial-modeling, ]
---

Modeling is an abstraction of a real-life situation. When it comes to financial modeling, one can think of this abstraction as a tool to empower business people to make sound decisions based on the quantification of model parameters. Especially if a _“quantifiable idea”_ appears in the mind of a business person, a financial model becomes handy to develop that particular idea to be structured as a decision point. Financial modeling informs mainly about an organization's major decisions, such as investments and operational planning.  

In this post, I would like to provide some of my reflections on financial modeling, based on personal experience from the banking industry. I will try to emphasize the factors affecting financial models to be useful for business decisions.  

Having spent years on MS Excel and VBA to built various financial models and business cases, I also buy into the idea of considering financial modeling is more of tradecraft than a science, as many of my seniors once told me. My initial temptations of mathematical representation of a decision model fade away after seeing failed results of strategy implementations in the real world. Furthermore, the business units have a tendency to blame the financial model for business failures, rather than the imperfect implementations of strategy. Nevertheless, these hapless discussions cannot eliminate financial modeling in the decision-making process.  

***Planning***
> ***"If you fail to plan, you are planning to fail."***  _Benjamin Franklin._

Planning is also a crucial part of financial modeling as well. 
Start with a quick one-page handwritten note, while having an initial discussion with the core team.  
This **plan** should minimally include;

* 1. **Purpose** : WHY do you need to develop a financial model? 
* 2. **Stakeholders** : WHO are the stakeholders of the model and outcomes.
* 3. **Data Sources** : WHAT information and sources needed for model development.
* 4. **Timeline**: Specify the timeline of the modeling and key milestones. 
* 5. **Deliverables** : mock-ups of final presentation or report.


***Scope***  

No financial model can demonstrate each and every aspect of any business framework. While avoiding _oversimplification_, the model scope should be restricted to reflect the most important aspects of the business. For instance, for a corporate financial model to reflect all revenue streams is always important, but you can reach to an optimal model complexity by applying [***Pareto principle***](https://en.wikipedia.org/wiki/Pareto_principle). You can eliminate complexity by using a combined proxy value for minor revenue items. 
Another example of scope is the purpose of the model. You should not try to realize multiple target functions under ever-changing constraint variables. Considering financial modeling as a [***discrete optimization problem***](https://en.wikipedia.org/wiki/Optimization_problem) will help you to focus on the most important decisions to model.   
You may either try to _minimize/maximize_ a single business target like sales, net profit, cost of goods sold, staff cost,  etc. under applicable _constraints_ (ie. production capacity, infrastructure regulatory thresholds, minimum staff to run the business) in a financial model.



***Assumptions and Inputs***  

Financial models are to be based on _“assumptions”_. Yet, the infamous rule: **“a model is only as good as its assumptions”** applies to success of the decision model. Therefore it is imperative to effectively communicate assumptions and restrictions of the modeling process with the model users or the stakeholders. Assumptions, even based on some simple calculations, should be strictly disclosed along with their dependents, right after the initial planning phase of the model.

Model inputs are another discussion point many times. Your data sources should be up-to-date, reliable, well documented, and repeatable for validation.  
Notice that input data collection  phase should not be long and distracting. In such cases, consider dropping that model portion to simplify, or post-pone for further enhancements. 

Focusing on making the model up-and-running, with minimum assumptions and barely necessary inputs will motivate the developer team to produce the final product. 


***Formatting***  

Starting from day one, specifying and adhering to a legend of colors to distinguish between inputs and output (calculations)will provide comfort for the developer to create and document the model. Typical conventions, such as making inputs blue color fonts, and formulas blacks. 
It’s important to clearly distinguish between inputs (assumptions) in a financial model, and output (calculations). This is typically achieved through formatting conventions, such as making inputs blue and formulas black. You can also use other conventions like shading cells or using borders.

 ***Model layout and design***  

As long as the model is structured in a logical and easy to follow design, the model can either be designed in one page or multiple tabs. For large models, a multiple-tabbed model is easier to understand and navigate. 

General accepted naming for sections in a financial model can be as follows: 

1. **Cover Page** (Model name, purpose, Contents/Sheets, Version history, authors' contact, disclaimers)
2. **Assumptions and Inputs** (also named Drivers, includes hardcoded inputs and parameters)  
3. **Model Calculation Group**
   * Balance sheet
   * Income statement
   * Cash Flow statement
4. **Outputs** (model highlights, ratios, charts etc.)
5. **Simulations - Sensitivity Analysis** (scenario-based calculations, decision criteria output)


***Documentation and Auditing***

Documentation is the most overlooked and least attractive part of the process. Financial modeling, in general, starts as a one time exercise and once its benefits are accepted in a company, it becomes a periodical task. Then it becomes indispensable to meet the following requirements with complete documentation. 

These requirements are:

>1. The Longevity of the model (because the model requires periodic updates)
>2. Audit requirements (as the importance of the model increases, there will be increasing scrutiny over your calculations)
>3. Transition potential (the modeler may switch to another position or a company)


Here we come to the end of this post. I will be revisiting this subject, if I found more words, worth to share.
