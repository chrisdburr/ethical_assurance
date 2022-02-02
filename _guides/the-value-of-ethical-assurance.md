---
title: The value of ethical assurance
excerpt: This guide explains why ethical assurance is important by looking at the challenges associated with regulating or governing the design, development, and deployment of data-driven technologies or AI. 
image_path: /assets/img/placeholder5.jpeg
published: false
---

In safety critical domains, such as aviation or healthcare, various procedures and tools exist to help project managers or decision-makers assess or evaluate whether a system is, for example, safe to operate or compliant with existing regulation. Some tools help manufacturers implement technical standards or design constraints (e.g., fire safety requirements). Others help auditors identify whether an organisation has carried out business lawfully (e.g., compliance checks).
One of these methods is _argument-based assurance_.

Argument-based assurance is a process for constructing an argument and supporting evidence for how a particular goal has been obtained (e.g. the safety or reliability of a product).
The outcome of this process is an {% glossary assurance case %}, which is a structured representation of the argument and evidence. For example, the following assurance case focuses on safety of a control system {% cite theassurancecaseworkinggroup2018 %}:

<img class="post-img" src="/assets/img/gsn.png" />

This example shows a general form of an assurance case, with a lot of details removed.
However, you can see that there is a clear goal at the top level of the case, towards which the lower-level claims are oriented.
The goal relates to the safety of a control system, and the lower-level claims are intended to provide assurance that the control system is "acceptably safe to operate".

The process of building an assurance case can be time-consuming, but there are many benefits of carrying out the associated steps:

- Initial project planning for an assurance case provides an opportunity to anticipate and pre-empt potential risks and adverse impacts associated with the project.
- These preliminary risk or impact assessments can assist internal reflection and deliberation within a project team by providing a systematic and structured means for evaluating how the development of a system or product may impact different groups of users of other affected stakeholders.
- Provisional reflective work can support subsequent mechanisms and processes of documentation (or, reporting) to ensure accountability (e.g. audits, compliance).
- Transparency can further build trust and confidence by promoting the adoption of best practices within and between industries or sectors (e.g. standards for warranted evidence) and help integrate shared practices into project lifecycles and connected value chains.

The above arguments set out what may be understood as _pragmatic_ or _instrumental_ arguments for the importance and value of reliable forms of assurance.
However, we are interested in _ethical_ assurance specifically.
Therefore, our arguments ought to go beyond appeal to merely pragmatic considerations.

This does not mean that the above claims have no bearing on ethical issues.
To the contrary, careful reflection on impact and risks could include an assessment into whether an automated decision-making system used in hiring would discriminate against certain groups of individuals.
However, ethical assurance is grounded in a commitment to inclusive dialogue and engagement with respect to the determination of relevant values and principles.

What this means is that the task of deciding on and defining the relevant goal(s) to which an assurance case is oriented is something that ought to be carried out with the participation of affected users and stakeholders.
A couple of illustrative examples can help explain this point.

### Example 1: Explainable AI in Healthcare

The processes by which an AI is developed to produce some behaviour (or, "make a decision") can be challenging to interpret and explain.
However, AI is also capable of supporting the assessment and diagnosis of various health issues.
While the systems being developed may be highly accurate for certain groups of patients, a key ethical principle of healthcare upheld by medical professionals is the support of informed consent.
In short, informed consent requires that any patient who is asked to consent to a medical procedure or intervention does so on the basis of a sufficient level of understanding (i.e., they are suitably "informed").
For an AI system to support the ethical principle of respect for informed consent, therefore, requires an awareness and understanding of what healthcare staff and patient groups take to be an appropriate explanation for how some system reached a decision.
While some patients may be happy with accepting or trusting the recommendations of a black-box AI system on faith alone, this is unlikely to be suitable assurance for all.

### Example 2: Automating Recommendations for City Infrastructure Planning

Where techniques such as machine learning excel is in the recognition of patterns in large-scale datasets.
For example, finding trending patterns on social media or predicting patterns of consumer spending habits.
This capacity for pattern recognition can be used to generate recommendations for a wide variety of decisions, ranging from what film to watch on Netflix to where the best route would be for a new transport link.
However, the generation of recommendations by algorithmic systems such as these, first requires a project team to agree on what they are trying to improve.
In the case of Netflix, this may be user engagement and satisfaction.
In the case of city planning decisions, it may be reduced congestion.
In the former case, a poor recommendation may not cause any significant harm—just a wasted evening watching a terrible film!
But in the latter case, the extent of harm can go beyond loss of economic productivity.
What if, say, the choice by the developers to train a machine learning algorithm to predict the best routes for a new transport link, based on the ability to ease congestion, overlooked the already poor and degrading transport infrastructure relied upon by carers and stay-at-home-parents in the outskirts of a city.
The algorithm may perform very well, but the decision to follow recommendation may end up implementing biased policy that could marginalise vulnerable communities that are not well served by existing transportation.

In the first of these examples, the key ethical issue was the need to ensure sufficient explainability from AI systems.
In the second, the example indicates how algorithmic systems can end up creating biased outcomes even when they are working as expected.
Both examples emphasise that ensuring the responsible and ethical design, development, and deployment of a data-driven technology demands more than a consideration of its technical properties.
Rather, it requires careful reflection and deliberation, in partnership with affected individuals, about the properties of the system when situated within the intended operating environment.

...

- This preparatory work can facilitate transparent communication between developers and affected stakeholders, helping to build trust