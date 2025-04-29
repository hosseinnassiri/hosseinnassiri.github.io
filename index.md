# Certified Azure Solution Architect Expert

{% for project in site.projects %}
    {{ project.title }}
{% endfor %}

I'm an experienced **Azure Solution Architect** with over 20 years of success designing and delivering cloud-native solutions. Specialized in Azure technologies, DevSecOps practices, and modern architecture frameworks across Finance, Capital Markets, Asset Management, and E-Commerce industries. Strong communicator, technical leader, and strategic thinker with a proven record of improving scalability, reducing costs, and enabling digital transformation.

## Core Skills

{% for skill in site.skills %}
*    {{ skill }}
{% endfor %}

## Certificates

<ul>
{% for certificate in site.certificates %}
    <li><a href="{{ certificate.url }}">{{ certificate.name }} {{ certificate.short_name }}</a></li>
{% endfor %}
</ul>
