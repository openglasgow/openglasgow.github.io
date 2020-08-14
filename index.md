---
layout: default
---

Welcome to the Open Glasgow Developer site.

Here you will find technical information and documentation about Data, APIs and more.

You can also visit our interactive API's on our [developer site](https://gcc.developer.azure-api.net/) and view documentation [here](./api).

### Open Glasgow Blog
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

##### How to find us
* [Twitter](https://twitter.com/openglasgow)
* [Facebook](https://facebook.com/openglasgow)
* [About Open Glasgow](./about.md)
* [Contact Open Glasgow](./contact.md)
