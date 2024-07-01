---
layout: home
author_profile: true
---

# Wenbo YI's Homepage

Welcome to Wenbo YI's Personal Homepage!

I am a [Your Position] in [Your Field] at [Your University/Institution]. [Brief introduction about your research and advisors]

[More detailed paragraph about your background and research interests]

## Recent Updates

{% for post in site.posts limit:3 %}
* {{ post.date | date: "%m/%d/%Y" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}