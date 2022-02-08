---
title: Instructions
author: chris
excerpt: This post has some useful instructions for authors.
image_path: /assets/img/wireframes.jpeg
tags: philosophy ethics
published: true
---

> note "I am a note"
> The body of the note goes here. Premonition allows you to write any `Markdown` inside the block.

This post has some instructions about how to use some of the plugins that are enabled on this site.

## Jekyll-Scholar

All blog posts can access references stored in a `bibliography.bib` file, which is defined in the site's `_config.yaml` file.

For example, this is a sentence with a citation {% cite burr2021 %}.

Citations can be added using the following code:

`{% cite author2022 %}`

A bibliography is automatically created at the end of the post.

## Jekyll-Tags

Tags can be added to the YAML frontmatter of posts using the following format:

`tags: tag1 tag2`

Tags are separated by spaces. If tags are multiple words, they should be put in the following format:

`tags: tag-one tag-two`

## Glossary

Glossary tooltips are supported by adding new items to the `glossary.yaml` file, which is located in the `_data` folder.
A new term should have the following format:

{% highlight yaml %}
- term: definiendum
  definition: The definition of the term.
  url: an optional url that can be used for further references
{% endhighlight %}

If this term is used in a post or guide, the following syntax will display the word as a tooltip:

{% highlight liquid %}
    {% raw %}{% glossary term %}{% endraw %}
{% endhighlight %}

Or, alternatively:

{% highlight liquid %}
    {% raw %}{% glossary term, display: <display name> %}{% endraw %}
{% endhighlight %}

Here are two examples of what these commands result in:

{% glossary assurance case %}

{% glossary assurance case, display: ethical assurance case %}

{% highlight javascript %}
document.write("JavaScript is a simple language for javatpoint learners");
{% endhighlight %}
