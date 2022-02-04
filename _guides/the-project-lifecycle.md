---
title: The project lifecycle—a structured approach to reflection and deliberation
excerpt: This post introduces the project lifecycle. A simple model to structure reflective and deliberative activities regarding the ethical properties of a data science or AI project.
image_path: /assets/img/placeholder6.jpeg
published: false
---

The use of AI technology in policing is controversial.
Specifically, the use of automated facial recognition to identify criminals or wanted suspects in public spaces has received significant opposition.
Two reasons for this controversy and backlash, among others, are as follows:

1. Automated facial recognition and surveillance is a further, unwanted restriction on civil liberties and a violation of reasonable expectations of privacy—even in public spaces.
2. The technology behind automated facial recognition has been demonstrated to exhibit racial bias. Those with darker skin are more likely to be incorrectly stopped by police as a result of inaccuracies in the system.

Both of these reasons make reference to ethical values.
The first makes reference to social and ethical values, such as the importance of liberty or neighbouring concepts such as respect for privacy.
Here, the objection appears to be, at first glance, about the decision to deploy the technology, rather than specific features of the technology itself.

The second reason addresses issues of fairness and equality.
However, it also makes direct reference to features of the technology—specifically, the fact that automated facial recognition systems often display bias towards individuals with darker skin.

If a project team were to reflect on these two reasons, they may conclude, on the basis of the first reason, that the development and deployment of the technology should not go ahead.
However, if they were to reflect on the challenge presented by the second reason, they may treat the problem as a technical challenge that could be "solved" by gathering more representative data or adjusting the algorithm's parameters to achieve a more balanced level of accuracy across the sub-groups of the population.

Both of these decisions represent actions taken in response to ethical reflection and deliberation—decisions taken at some point in a _project's lifecycle_.
This is not to say that both decisions are morally equivalent, as we will see shortly.
But to make this point clear, we need to have a framework for locating such decisions and actions within the context of a project's lifecycle.

## The ML/AI Project Lifecycle

The following diagram is a model of a typical lifecycle for a project that involves the design, development, and deployment of a machine learning algorithm or AI system.

<img class="post-img" src="/assets/img/project-lifecycle.png" />

The central segments carve up the project lifecycle into three over-arching stages:

1. Project Design
2. Model Development
3. System Deployment

The outer labels indicate activities that are associated with these stages[^activities].
In some cases, the activities overlap with two over-arching stages, demonstrating that the boundaries between activities are, in practice, not clearly defined.

While this model has a high degree of technical accuracy it was not designed to capture the precise manner in which ML/AI projects will or ought to be carried out within an organisation.
For instance, the model does not address the common practice of Agile or iterative processes in which earlier stages are returned to after testing provisional ideas.
Instead, the model has been designed to aid _reflection_ and _deliberation_ regarding the decisions and actions that ought to be taken during the process of ethical assurance.

Let's return to the facial recognition example to see how this works.

### Avoiding Bias

As we've already seen, one reason why an AI system may exhibit bias is because the dataset it has been trained on is insufficiently _representative_.
In short, this means that the data used to train the system is unbalanced, and likely has a higher proportion of instances for one group than another.

For example, imagine if the following (simplified) graphic represented a dataset being used to train a model for facial recognition[^cnn]:

[^cnn]: This will most likely be a {% glossary convolutional neural network %}.

As you can see, the proportion of lighter skinned males in this dataset is higher than all other groups.
Therefore, we can expect that the algorithm will have a higher level of accuracy for individuals that are representative of this class.
In contrast, those individuals that are not well represented in the training data are likely to misclassified or identified.

This general rule of representation applies to all cases of machine learning.
However, the consequences of poor performance can only be understood at the social level.
In the context of an automated facial recognition system, for instance, low accuracy for a sub-group of the population increases the chance of being incorrectly stopped by police.
In a social environment where there are existing tensions between the police and local communities, this outcome could exacerbate existing social injustices.

This raises an important question—one that is directly connected to the project lifecycle: what actions should a project team take, and when, to avoid acting unethically?

### Project Design or Model Development?

A common answer, and active research programme in fair ML, is to address the class imbalance during the model development stage, using a variety of methods, which are designed to even out the distribution of errors across the subgroups.
However, as you can see from the project lifecycle, this intervention comes at a fairly late stage.

What about if we move upstream?

If we take a few steps back to the data extraction and procurement stage, the project team could avoid the need to adjust the training parameters by collecting a more representative dataset.
This could help improve the accuracy for certain sub-groups, and avoid the introduction of bias into the system.

But is this still the best action to take?

If we go all the way to the start—back to the 'project planning' activities—the project team could carry out engagement activities with affected users to consider whether they believe the system to be a responsible use of technology.

As the following news events suggest, public attitudes towards automated facial recognition are fairly negative.
That is, a lot of people believe the technology to be unethical, and there have also been legal challenges to the deployment of the technology.




[^activities]: A description for each of these activities is provided in [a separate guide](lifecycle-activities.md).
