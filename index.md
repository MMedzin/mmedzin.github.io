---
layout: page
title: Welcome to my blog
---

Hey there! I'm Michał, and this is my corner of the internet, where I share my thoughts and projects related to data science, Python, and more. Feel free to explore and learn with me.

## Latest Posts

<div class="blog-index">  
{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
</div>

## About Me

I'm a data scientist with multiple other passions. Here's a bit about me:

- **Name:** Michał Mędzin
- **Professional Interests:** Data Science, Machine Learning, Python, and more.
- **Other Interests:** Cooking, Baking, Yoga, Wim Hof Method, Drawing, and more.

## Connect with Me

- GitHub: [github.com/MMedzin](https://github.com/MMedzin)
- LinkedIn: [linkedin.com/in/michał-mędzin/](https://www.linkedin.com/in/michał-mędzin/)

## Contact

Feel free to contact me at [michal.medzin@protonmail.com](mailto:michal.medzin@protonmail.com) if you have any questions or would like to collaborate on a project.

Happy reading and coding!
