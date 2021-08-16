---
layout: page #speaker-overview
---

# Invited speakers

<br>
<div>
    {% assign number_printed = 0 %}
    {% for s in site.data.speakers %}

    {% assign even_odd = number_printed | modulo: 2 %}

    {% if even_odd == 0 %}
    <div class="row" style="margin-bottom:15px;">
    {% endif %}

    <div class="col-sm-6 clearfix">
        <img src="{{ site.url }}{{ site.baseurl }}/assets/headshots/speakers/{{ s.photo }}" 
        class="img-responsive" width="22%" style="float: left; border-radius: 50%; vertical-align:top; margin-right: 15px; border:1px solid #999999;" />
        {% if s.www %}
        <p style="margin:0; "><a href="{{ s.www }}" style="font-weight:bold">{{ s.name }}</a>
        {% else %}
        <p style="margin:0; font-weight:bold">{{ s.name }}
        {% endif %}
        </p>
        <!-- ({{ s.affil }})</p> -->
        <p style="font-size:0.9rem;text-align:justify;">{{ s.affil }}</p>
        <!-- <p style="font-size:0.9rem;text-align:justify;">{{ s.bio }}</p> -->
    </div>

    {% assign number_printed = number_printed | plus: 1 %}

    {% if even_odd == 1 %}
    </div>
    {% endif %}

    {% endfor %}

    {% assign even_odd = number_printed | modulo: 2 %}
    {% if even_odd == 1 %}
    </div>
    {% endif %}
</div> 