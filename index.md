---
subject: World
---
# Hello {{ subject }}

You can type here!

- [Markdown](/docs/languages/markdown/)
- [Liquid](/docs/languages/liquid/)

## Posts

{%- for post in collections.posts %}
- [{{ post.data.title }}]({{ post.url}})
{%- endfor %}

Built with {{ eleventy.generator }}_
