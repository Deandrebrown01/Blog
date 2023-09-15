# Dre's Blog

**Hello Welcome to my blog!!!!!!!!**

The world of coding and software is a great thing to experience. Look more at my blog if you wanna see coding and cool things about coding.

![A good photo of me](/assets/IMG-0373%20(3).jpg)


## Recent Posts
<ul>
{% for post in site.posts %}
<li>
<a href="/blog{{ post.url }}">{{post.title}}</a>
</li>
{% endfor %}
</ul>





