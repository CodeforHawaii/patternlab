# Code for Hawaii's Pattern Lab

A pattern lab is a style guide for web development, it guides not only how our sites look but how they are structured.
This gives greater unity across all of our projects. If it works well, it allows us to speak a common design language through code.
And for people who use our tools it helps to see a unified style.

But it's not restrictive -- it should not impose limitations.
It's a living document that should be updated regularly to reflect patterns that are common among our projects.

This repository contains both the uncompiled assets which can be built, and the compiled site in the [public](https://github.com/CodeforHawaii/patternlab/tree/master/public) folder.



## Deployment

For some tips on deployment I recommend checking out [Balmore Botero's readme](https://github.com/balmoreboterolacity/lacitypatterns)
for creating the [LA City patternlab](http://contact.lacity.org/style/?p=all).



## Other useful resources
- [Code for America's style guide](http://codeforamerica.clearleft.com/)
- [List of style guides from policyviz](http://policyviz.com/style-guides/)
- [U.S. Web Design Standards](https://playbook.cio.gov/designstandards/)
- [The Sunlight Foundation's Data Visualization Style Guidelines](http://sunlightfoundation.com/blog/2014/03/12/datavizguide/)




## About Pattern Lab
- [Pattern Lab Website](http://patternlab.io/)
- [About Pattern Lab](http://patternlab.io/about.html)
- [Documentation](http://patternlab.io/docs/index.html)
- [Demo](http://demo.patternlab.io/)
- [Requirements](http://patternlab.io/docs/requirements.html)
- [How Patterns Are Organized](http://patternlab.io/docs/pattern-organization.html)

The PHP version of Pattern Lab is, at its core, a static site generator. It combines platform-agnostic assets, like the [Mustache](http://mustache.github.io/)-based patterns and the JavaScript-based viewer, with a PHP-based "builder" that transforms and dynamically builds the Pattern Lab site. By making it a static site generator, Pattern Lab strongly separates patterns, data, and presentation from build logic.
