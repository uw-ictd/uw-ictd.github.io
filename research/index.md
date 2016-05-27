---
layout: default
title: Research Projects
---

Our research focuses on how technology can improve the lives of underserved populations in low-income regions. Our research has a wide range of themes. The *HCI* theme addresses challenges in interfaces for people with low literacy, even for basic technologies like SMS or voice calls. The *system* theme explores how complicated systems can be built with the assumption that the user has little or no IT support. The *networks and communication* theme focuses on building systems or applications that connect people in rural areas that have little or no connectivity available. The *security* theme looks at all possible threats that current systems in low resource area are exposed to and how to handle those threats. The *behavior change communication* theme explores how technology can educate and introduce best practices among people in slums and/or rural parts of the world. The *global health* theme looks at applications that support analysis, interfaces and education for better health care in developing regions. The *Data Analytics* theme aims to provide support for data cleaning, understanding the data and running complex analysis for users with little knowledge about the data or the analytics process.

{% include_relative hci.md %}

<dl class="dl-horizontal">
{% for project in site.data.projects %}
	{% for ar in project.area %}
		{% if ar == "hci" %}
			<dt>{{ project.title }}</dt>
  			<dd>{{ project.description }} {% if project.url %} <a href="{{ project.url |escape }}"> More >> </a> {% endif %}</dd>
		{% endif %}
	{% endfor %}
{% endfor %}
</dl>

{% include_relative systems.md %}

<dl class="dl-horizontal">
{% for project in site.data.projects %}
	{% for ar in project.area %}
		{% if ar == "systems" %}
			<dt>{{ project.title }}</dt>
  			<dd>{{ project.description }} {% if project.url %} <a href="{{ project.url |escape }}"> More >> </a> {% endif %}</dd>
		{% endif %}
	{% endfor %}
{% endfor %}
</dl>

{% include_relative networks.md %}

<dl class="dl-horizontal">
{% for project in site.data.projects %}
	{% for ar in project.area %}
		{% if ar == "networks" %}
			<dt>{{ project.title }}</dt>
  			<dd>{{ project.description }} {% if project.url %} <a href="{{ project.url |escape }}"> More >> </a> {% endif %}</dd>
		{% endif %}
	{% endfor %}
{% endfor %}
</dl>

{% include_relative security.md %}

<dl class="dl-horizontal">
{% for project in site.data.projects %}
	{% for ar in project.area %}
		{% if ar == "security" %}
			<dt>{{ project.title }}</dt>
  			<dd>{{ project.description }} {% if project.url %} <a href="{{ project.url |escape }}"> More >> </a> {% endif %}</dd>
		{% endif %}
	{% endfor %}
{% endfor %}
</dl>

{% include_relative behavior.md %}

<dl class="dl-horizontal">
{% for project in site.data.projects %}
	{% for ar in project.area %}
		{% if ar == "behavior" %}
			<dt>{{ project.title }}</dt>
  			<dd>{{ project.description }} {% if project.url %} <a href="{{ project.url |escape }}"> More >> </a> {% endif %}</dd>
		{% endif %}
	{% endfor %}
{% endfor %}
</dl>


{% include_relative health.md %}

<dl class="dl-horizontal">
{% for project in site.data.projects %}
	{% for ar in project.area %}
		{% if ar == "health" %}
			<dt>{{ project.title }}</dt>
  			<dd>{{ project.description }} {% if project.url %} <a href="{{ project.url |escape }}"> More >> </a> {% endif %}</dd>
		{% endif %}
	{% endfor %}
{% endfor %}
</dl>

{% include_relative data.md %}

<dl class="dl-horizontal">
{% for project in site.data.projects %}
	{% for ar in project.area %}
		{% if ar == "data" %}
			<dt>{{ project.title }}</dt>
  			<dd>{{ project.description }} {% if project.url %} <a href="{{ project.url |escape }}"> More >> </a> {% endif %}</dd>
		{% endif %}
	{% endfor %}
{% endfor %}
</dl>

