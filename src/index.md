---
layout: document
subtitle: ''
tags:
- homepage

---
The Organised Services Operating Model (OSOM) is a template operating
model to help organisations adopt a service-based approach. This is in
opposition to a functional model, where capabilities are grouped by
skills and ownership of the delivery to users is an endeavour shared
between those functions.

The operating model has evolved by encouraging a [common set of good behaviours]({{ '/doctrine' | url }}) at multiple organisations and discovering an organisational design and supporting processes that occur as a consequence.

The key components of OSOM are an executive capability that provides
oversight & governance and a network of services that progress through
a simple [service lifecycle]({{ '/lifecycle' | url }}) compatible with the
[Government Digital
Service's](https://www.gov.uk/government/organisations/government-digital-service)
[service manual](https://www.gov.uk/service-manual).

[![a diagram showing an overview of the various parts of the operating model]({{ '/assets/img/opmodel-overview.jpg' | url }} "OSOM
Overview")]({{ '/assets/img/opmodel-overview.jpg' | url }} "Operating model
overview diagram")

## A template operating model

OSOM is a template operating model. Each organisation is different,
and few organisations would be directly mappable onto OSOM
directly. Instead, it forms a general approach that should be
carefully adapted as needed to the organisation.

The key to adapting an operating model for any organisation is to be aware of the trade-offs being made with each compromise, both positive and negative. That way, governance can be established to balance the negative consequences, and full advantage can be taken of positive consequences.

## Previous documentation

This site is an evolution of the original [OSOM
documentation](http://stance.consulting/osom/). While the
documentation almost certainly remains incomplete, this site takes
precedence and overrides any contradictions between the two.

## Elements of OSOM

![]({{ '/assets/img/osom-overview.svg' | url }})

### The executive

The [OSOM executive]({{ '/executive' | url }}) governs the network of services and
holds the managers of those services to account through various
mechanisms documented in terms of reference.

The executive also has a role in advocating and monitoring the
adoption of [doctrine]({{ '/doctrine' | url }}) throughout the organisation, which
is a collection of 40 universally useful patterns of behaviour.

### The service network

[OSOM services]({{ '/services/' | url }}) address the needs of users. For any given
service, the users may be external to the organisation, internal, or a
mixture of both.

Each service is built & operated by a Service Manager, who is
accountable for the service and the team required in all its lifecycle
phases - from discovery until its eventual retirement.

## Recent changes

{% for article in collections.all limit:5 reversed %}
{% if article.data.subtitle.length > 0 %}
1. [{{ article.data.subtitle }}]({{ article.url | url }})
{% endif %}
{% endfor %}
