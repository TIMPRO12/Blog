# <Ins>Starting Up</Ins>


<ul>
    {% for post in site.post %}
        <li>
            <a herf="{{post.url | relative_url }}">{{ post.title }} </a>
        </li>
    {% endfor %}
</ul>