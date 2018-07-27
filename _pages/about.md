---
title: About
layout: page
---

# About
The CDS Method Cards are a collection of tools that describe how our teams put human-centered design into practice. They have been derived from the federal government's 18F Methods, modified for civic purposes. We've gathered them here and created simplified instructions so that Chicago institutions and departments can view the design services the city offers, and help them implement this playbook into their own process. These cards are focused on design in the context of digital services, but can be adapted to non-technical design projects as well.

## The basics of human-centered design
Human-centered design is a methodology that incorporates feedback from the people for whom you are designing throughout the design process. The goal of human-centered design is to end up with a solution that is tailored to meet people's needs, with little wasted effort and reduced risk. [Learn more about the benefits and techniques of human-centered design](http://www.designkit.org/human-centered-design).

## Using the Method Cards
The Method Cards are broken up into the four broad design phases your team is likely to go through during a project. While some cards refer to other methods, you may use them independently. You do not need to use all the cards in a section or complete certain tasks before moving on to others. Take whatever cards are most useful to your team and incorporate more tools as you’re ready.

## Go behind the scenes
As the CDS Methods are a fork of 18F's product, these cards are completely open source. You are free to copy, share, or reuse them [as you wish](https://github.com/chicago/design-methods/blob/staging/LICENSE.md). We also welcome input from the public, whether it’s correcting a typo or suggesting a new method to include. You can see our [guidelines for contributing on GitHub](https://github.com/chicago/design-methods/blob/staging/CONTRIBUTING.md).

## Release notes

{% for release in site.data.releases %}
### {{ release.name }}
<p class="site-subheading">{{ release.published_at | date: "%B %d, %Y" }}</p>
{{ release.body | markdownify }}
{% endfor %}
