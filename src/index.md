---
meta:
  title: Home page
  description: Find information about the Durango Colorado tech community.
layout: base
eleventyNavigation:
  key: Home
  order: 1
---

<p class="lead">Find information about the Durango, CO tech community below!</p>

## Groups

### Local
{% for group in local.groups %}

- {{ group.name }} ({{ group.status }}) | {% if group.meetup %}[Meetup]({{ group.meetup }}){% endif %}{% if group.slack %}, [Slack]({{ group.slack }}){% endif %}{% if group.mailingList %}, [Mailing List]({{ group.mailingList }}){% endif %}| {%if group.note %}{{ group.note }}{% endif %}
{% endfor %}

### Regional

{% for group in regional.groups %}

- {{ group.name }} ({{ group.status }}) | {% if group.meetup %}[Meetup]({{ group.meetup }}){% endif %}{% if group.slack %}, [Slack]({{ group.slack }}){% endif %}{% if group.mailingList %}, [Mailing List]({{ group.mailingList }}){% endif %} | {%if group.note %}{{ group.note }}{% endif %}
{% endfor %}

## Coworking Spaces

- [DurangoSpace](https://durangospace.com/)
- [R Space](https://www.rspacedurango.com/)
- [Center for Innovation](https://www.fortlewis.edu/innovation/)
- [Tech Flex](https://techflexdurango.com/)
- [Smiley Building](https://smileybuilding.com/)

## Accelerators

- [SCAPE](https://www.goscape.org/) - Southwest Colorado Accelerator Program for Entrepreneurs
- [Center for Innovation](https://www.fortlewis.edu/innovation/)
- [Startup Colorado](https://startupcolorado.org/)

## Other

- [West Slope Startup Week](https://www.westslopestartupweek.com/)