---
layout: post
title: The Value of Ethical Assurance
author: chris
excerpt: "This guide discusses the value of ethical assurance beyond its pragmatic role in supporting governance and compliance, and offers a couple of case studies to help demonstrate its central claims."
image_path: /assets/img/landscape.jpeg
published: true
---

In safety critical domains, such as aviation or healthcare, a wide variety of procedures and tools exist to help project managers or decision-makers assess and evaluate whether a system is, for example, safe to operate or compliant with existing regulation.
Some of these tools help manufacturers implement technical standards or design constraints (e.g., fire safety requirements). Others help auditors identify whether an organisation has carried out business lawfully (e.g., compliance checks).

One of these methods is _argument-based assurance_.

As we saw in our [first guide](what-is-ethical-assurance.md), argument-based assurance is a methodology for constructing a structured case to demonstrate and justify how a particular goal has been obtained (e.g. the safety or reliability of a product).
The outcome of this process is an {% glossary assurance case %}, which is a structured representation of the argument and evidence.
For example, the following assurance case focuses on safety of a control system {% cite theassurancecaseworkinggroup2018 %}:

<img class="post-img" src="/assets/img/gsn.png" />

This example shows a general form of an assurance case[^gsn], with a lot of details removed.
However, you can see that there is a clear goal at the top level of the case, towards which the lower-level claims are oriented.
The goal relates to the safety of a control system, and the lower-level claims are intended to provide assurance that the control system is "acceptably safe to operate".

[^gsn]: This particular assurance case uses the goal-structuring notation (GSN) community standard {% cite theassurancecaseworkinggroup2018 %}.

The process of building an assurance case can be time-consuming, but there are many benefits of carrying out the associated steps.

> info "Benefits of Assurance Cases"
> - Initial project planning for an assurance case provides an opportunity to anticipate and pre-empt potential risks and adverse impacts associated with the project.
> - These preliminary risk or impact assessments can assist internal reflection and deliberation within a project team by providing a systematic and structured means for evaluating how the development of a system or product may impact different groups of users of other affected stakeholders.
> - Provisional reflective work can support subsequent mechanisms and processes of documentation (or, reporting) to ensure accountability (e.g. audits, compliance).
> - Transparency can further build trust and confidence by promoting the adoption of best practices within and between industries or sectors (e.g. standards for warranted evidence) and help integrate shared practices into project lifecycles and connected value chains.

These items set out what may be understood as _pragmatic_ or _instrumental_ arguments for the importance and value of reliable forms of assurance.
However, we are interested in _ethical_ assurance specifically.
Therefore, our arguments ought to include but also go beyond the appeal to merely pragmatic considerations.

## Ethical Value
Ethical assurance is grounded in a commitment to inclusive dialogue and engagement with respect to the determination of relevant values and principles.
This is achieved through the participation and engagement of stakeholders and affected users in key stages of a [project's lifecycle](the-project-lifecycle.md).

The value of this participatory method is, again, about more than compliance with legal requirements (e.g., to avoid discriminatory harm). 
Rather, it is about adopting a more responsible approach to the design, development, and deployment of data-driven technologies by identifying how such systems give rise to opportunities and risks, which impact upon individuals and groups of people in myriad ways.
To put it another way, the initial benefit of developing a system that the project team identify may not be seen as a benefit to all, and in some cases may lead to negative consequences that were not anticipated.
Therefore, robust engagement and participation can help ensure that a project and the resulting system supports a wide variety of goals—underpinned by consideration and awareness of key ethical values.

A couple of illustrative examples can help explain these points further.

### Example 1: Explainable AI in Healthcare

<img class="post-img" src="/assets/img/participatory-design.png" />

The processes by which an AI system operates can be challenging to interpret and explain.
In cases where no explanation for the behaviour of a system are necessary, this may poses no real cocnern. 
However, AI is also capable of supporting the assessment and diagnosis of various health issues, and in healthcare there is a need to support a key ethical value of *informed consent*.
In short, when a patient is required to consent to some intervention (e.g., an operation or prescription), the healthcare professional has a responsibility to ensure that the patient is informed about the reasons behind the recommendation.

There are many reasons why such a value exists, including *respect for the autonomy* of patients and their right to make decisions about their health, and the *mitigation of risks* involving the inherent uncertainty of healthcare. 
While this second point may appear, at first glance, to be simply a matter of healthcare systems minimising their legal liability, it is in fact closely interwoven with the first value.

Patients vary in terms of the level of risk they are willing to accept. 
While some patients will be highly risk averse, others may be happy to trial experimental new procedures or medications in the hope that it improves their health.
The level of risk that a patient is willing to accept will, invariably, depend on a number of factors, including their personality and their level of understanding about the medical intervention being considered.

This is why informed consent is such an important ethical value in medicine, and is also why explainable AI is an absolute necessity in healthcare.

At present, the data-driven technologies being developed and used in medicine and healthcare—whether for use in radiology, drug discovery, or triage and assessment—can vary widely in their level of accuracy for certain groups of patients.
As such, if a technology is used to support the decision-making of healthcare professionals, it's behaviour needs to be interpretable and explainable.
While some patients may be happy with accepting or trusting the recommendations of a black-box AI system on faith alone, this is unlikely to be the case for all.

Here, then, the existence of an assurance case that is oriented towards the goal of explainability has value beyond compliance with legal or regulatory considerations.
It also has ethical value in supporting the _autonomy of patients_ by making informed decisions about their health and well-being.

### Example 2: Automating Recommendations for City Infrastructure Planning
Techniques such as machine learning excel in pattern recognition tasks involving large-scale datasets. 
For example, finding trending patterns on social media or predicting patterns of consumer spending habits.
This capacity for pattern recognition can be used in conjunction with ranking and sorting algorithms to generate automated recommendations to influence or support a wide-range of decisions.

> list "Example Objectives of Recommendation Systems"
> 1. **Media Streaming**: to recommend media, such as movies or music that a user is likely to enjoy (e.g., Netflix or Spotify).
> 2. **Social Media**: to sort and display posts to a user that is likely to maximise their engagement (e.g., Twitter, Facebook)
> 3. **E-Commerce**: to advertise products to a user that are to generate revenue (e.g. Amazon, Google Ads)
> 4. **Navigation System**: to offer several routes to the user, which optimise relevant factors (e.g., shortest distance, avoidance of tollls)
> 5. **Decision Support Systems**: to augment a user's intelligence by recommending a course of action (e.g., healthcare assessment)

The final example in the above list is fairly generic.
So, let's make it more specific.

Let's consider the case of a city planner who is tasked with reducing congestion by choosing where to prioritise the development of traffic infrastrcture upgrades. What are the ethical values associated with this project?

Obviously, a bad decision will have economic impacts on the city (e.g., wasted public resources, increased pollution from idling engines). This economic value has ethical significance, but is not the full picture.

What if, say, the developers chose to train a machine learning algorithm to predict the best routes for a new transport link, based on the objective of 'easing congestion'?
The manner in which this objective is specified could lead to a policy being selected that increases social inequality.
For instance, the goal of 'reduced congestion' is likely to focus on busy routes into the centre of the city to the neglect of already poor and degrading transport infrastructure on the outskirts of the city. 
However, these latter routes are more likely to be relied upon by carers and stay-at-home-parents who move between residential boroughs or districts, rather than using commuter lines.

This is not just a hypothetical scenario.
It is an issue that affects many cities and belies a hidden gender bias due to the fact that women are more likely to be stay-at-home parents or carers (e.g., for elderly parents).[^hidden]
[^hidden]: This example, and many others, is detailed further in the book, 'Invisible women: exposing data bias in a world designed for men' by Caroline Criado Perez {% cite criadoperez2020 %}

The algorithm may perform very well, but the decision to follow recommendation may end up implementing biased policy that could marginalise vulnerable communities that are not well served by existing transportation.

As such, the example also indicates how algorithmic systems can end up creating biased outcomes even when they are working as expected, but optimised for a goal that is poorly aligned with key ethical values (e.g., social justice).

* * *

The above cases help to demonstrate how argument-based assurance can support ethical values. 
However, these are just two examples based on specific principles—there are many more ethical values and principles that are relevant to the design, development, and deployment of a data-driven technologies.

Identifying these values and principles, and weaving them into a clear normative goal for an ethical assurance case requires careful reflection and deliberation, in partnership with affected individuals and stakeholders. 
In subsequent guides, we will look at how certain properties of a project or system need to be established to be confident that ethical goals have been obtained.

<h3>Footnotes</h3>
