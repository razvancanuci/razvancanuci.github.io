---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
🚀 I am an experienced and very adaptable software engineer in designing, developing, and optimizing scalable applications. I specialize in full-stack and backend development, working with modern technologies to build efficient and high-performing systems.

Always learning and exploring new technologies to stay ahead in the industry. 🚀

Let's stay connected! 🤝

<div class="row">
{% include about/skills.html title="Programming Languages" source=site.data.programming-skills %}
{% include about/skills.html title="Technologies" source=site.data.technologies-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

# **Experience**
<div class="row">
{% include about/timeline.html %}
</div>

# **Education**
<div class="row">
{% include about/timeline-education.html %}
</div>