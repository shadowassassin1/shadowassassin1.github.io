<nav>
    <ul>
        {% for item in site.navigation %}
            <li>
                <a href="{{ item.url }}">{{ item.text }}</a>
            </li>
        {% endfor %}
    </ul>
</nav>

