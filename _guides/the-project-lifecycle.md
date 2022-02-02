---
title: The project lifecycle—a structured approach to reflection and deliberation
excerpt: This post introduces the project lifecycle. A simple model to structure reflective and deliberative activities regarding the ethical properties of a data science or AI project.
image_path: /assets/img/placeholder6.jpeg
published: false
---

The use of artificial intelligence in policing is controversial.
Most notably, the use of automated facial recognition technologies to identify criminals or wanted suspects in public spaces.

Two reasons for this controversy, among others, are as follows:

1. Automated surveillance is a further, unwanted restriction on civil liberties and a violation of reasonable expectations of privacy.
2. The technology behind automated facial recognition has been demonstrated to exhibit racial bias. Those with darker skin are more likely to be incorrectly stopped by police as a result of inaccuracies in the system.

Both of these reasons make reference to ethical values. The first makes reference to social and ethical values, such as the importance of liberty or neighbouring concepts such as respect for privacy. Here, the objection appears to be, at first glance, about the decision to deploy the technology, rather than specific features of the technology itself.

The second reason addresses issues of fairness and equality. However, it also makes direct reference to features of the technology—specifically, the fact that automated facial recognition systems often display bias towards individuals with darker skin.

If a project team were to reflect on these two reasons, they may conclude, on the basis of the first reason, that the development and deployment of the technology should not go ahead. However, if they were to reflect on the challenge presented by the second reason, they may treat the problem as a technical challenge that could be "solved" by gathering more representative data or adjusting the algorithm's parameters to achieve a more balanced level of accuracy across the sub-groups of the population.

Both of these decisions represent actions taken in response to ethical reflection and deliberation. This is not to say that both decisions are morally equivalent, as we will see shortly. But to make this point clear, we need to have a framework for locating such decisions and actions within the context of a project's lifecycle.

## The ML/AI Project Lifecycle

The following diagram is a model of a typical lifecycle for a project that involves the design, development, and deployment of a machine learning algorithm or AI system.

<img class="post-img" src="/assets/img/project-lifecycle.png" />

The central segments carve up the project lifecycle into three over-arching stages:

1. Project Design
2. Model Development
3. System Deployment

The outer labels indicate activities that are associated with these stages. In some cases, the activities overlap with two over-arching stages, demonstrating that the boundaries between activities are, in practice, not clearly defined.

While this model has a high degree of technical accuracy it is not designed to capture the exact manner in which ML/AI projects will or ought to be carried out in all organisations. For instance, the model does not address the common practice of Agile methods or iteration whereby earlier stages are returned to after testing provisional ideas. Instead, it has been designed to aid reflection and deliberation regarding the decisions and actions that ought to be taken during the process of ethical assurance.

Let's return to the facial recognition example to see how this works.

### Project Design or Model Development?

As we've already seen, one reason why an AI system may exhibit bias is because the dataset it has been trained on is insufficiently _representative_. In short, this means that the data used to train the system is unbalanced, and likely has a higher proportion of instances for one group than another.

For example, imagine if the following graph represented the dataset the project team were using to train their automated facial recognition system:


