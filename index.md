---
layout: default
---
# PS C:\\> systeminfo
Random security blog OwO

# PS C:\\> Get-Process
{:id="posts"}

<ul>
{% for post in site.categories.posts %}

{% if post.en %}
<li>{{ post.title }} :: <a href="{{ post.url }}" title="{{ post.description }}">en</a> :: <a href="{{ post.pt }}" title="{{ post.description_pt }}">pt_br</a></li>
{% endif %}

{% endfor %}
</ul>

# PS C:\\> whoami /all
{:id="about"}

I'm me :3