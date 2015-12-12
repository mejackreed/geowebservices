---
layout: default
---

# geoservices

Companies, government agencies, NGO's, and educational institutions provide geospatial data to the public in many ways. A common way to do this is through geospatial [web services](https://en.wikipedia.org/wiki/Web_service). Navigating the services available and how to use them can often be cumbersome. [geoservices]({{site.baseurl}}) aims to provide clear explanations, with examples of how to use them.

## What are geospatial web services?

A web service is just a way to communicate over the internet. Geospatial web services are used to obtain and transport information about geospatial data on the internet.

## What types of services are available?

{% for my_page in site.pages %}
  {% if my_page.title %}
  <a class="page-link" href="{{ my_page.url | prepend: site.baseurl }}">{{ my_page.title }}</a>
  {% endif %}
{% endfor %}

## About geoservices.io
geoservices.io was inspired by

### Thanks
A hat tip to [Tom MacWright](http://www.macwright.org/) and the contributors of [mapschool.io](http://mapschool.io/) for inspiring this.
