---
title: "About"
layout: about
---



<!-- Socials -->
{% if site.socials %}

## Socials

    <ul>
        {% if site.socials.github %}
            <li>{% include icon-github.html username=site.socials.github label='GitHub' %}</li>
        {% endif %}

        {% if site.socials.trakt %}
            <li>{% include icon-trakt.html username=site.socials.trakt label='Trakt' %}</li>
        {% endif %}

        {% if site.socials.twitter %}
            <li>{% include icon-twitter.html username=site.socials.twitter label='Twitter' %}</li>
        {% endif %}

        {% if site.socials.youtube %}
            <li>{% include icon-youtube.html username=site.socials.youtube label='YouTube' %}</li>
        {% endif %}
    </ul>
{% endif %}
