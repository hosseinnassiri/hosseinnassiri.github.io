# Certified Azure Solution Architect Expert

{% for project in site.projects %}
    {{ project.title }}
{% endfor %}

I'm an experienced **Azure Solution Architect** with over 20 years of success designing and delivering cloud-native solutions. Specialized in Azure technologies, DevSecOps practices, and modern architecture frameworks across Finance, Capital Markets, Asset Management, and E-Commerce industries. Strong communicator, technical leader, and strategic thinker with a proven record of improving scalability, reducing costs, and enabling digital transformation.

## Core Skills

* Azure Cloud Architecture (IaaS, PaaS, SaaS)
* Microservices, Event-Driven Architecture
* Infrastructure as Code (IaC) using ARM templates, Bicep, Terraform
* Azure Networking, Security, Identity & Access Management
* Azure Governance, Compliance, and Cost Optimization
* Data Governance, Analytics (Blob Storage, Data Lake, Data Factory)
* DevSecOps (SAST, DAST, Secure CI/CD Pipelines)
* Cross-functional Leadership & Team Management

## Certificates

<ul>
{% for certificate in site.certificates %}
    <li><a href="{{ certificate.url }}">{{ certificate.name }} {{ certificate.short_name }}</a></li>
{% endfor %}
</ul>
