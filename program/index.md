---
layout: page #program
---

# Program

<br>
Information about invited speakers can be found <a href="{{ site.baseurl }}/speakers">here</a>. 
Please note that all times are in Eastern Time (New York). The final program is subject to change.

<!-- <script type="text/javascript">
   function toggle_visibility(id) {
       var e = document.getElementById(id);
       if(e.style.display == 'block')
          e.style.display = 'none';
       else
          e.style.display = 'block';
   }
</script> -->

<table class="styled-table">
    <thead>
        <tr>
            <th></th>
            <th>Time (ET)</th>
            <th>Event</th>
            <th>Speaker</th>
            <th>Platform</th>
        </tr>
    </thead>
    <tbody>
        <tr class="mingle-row">
            <td></td>
            <td>08:45</td>
            <td>Poster preview</td>
            <td>-</td>
            <td>Gather</td>
        </tr>
        <tr>
            <td></td>
            <td>09:00</td>
            <td>Opening remarks</td>
            <td><em>Organizers</em></td>
            <td>Zoom</td>
        </tr>
        <tr class="session-row">
            <td style="text-align:center;" rowspan=5>Session 1</td>
        </tr>
        <tr>
            <td>09:10</td>
            <td>
            {% assign n = "Peter Hagoort" %}
            {% assign s = site.data.speakers | find:"name", n %}
            Invited talk: {% if s.talk_title %}"{{ s.talk_title }}"{% else %}TBD{% endif %}
            {% if s.talk_abstract %}<br><br><p style="font-size:0.75rem;">{{ s.talk_abstract }}</p>{% else %}{% endif %}
            <!-- Invited talk: {% if s.talk_title %}"{{ s.talk_title }}"{% else %}TBD{% endif %}
                <br><button class="btn-primary btn-sm" style="margin-top:0.75rem;margin-bottom:0.75rem;" onclick="toggle_visibility('abstract1')">Abstract</button>
                <div style="font-size:0.75rem;display:none;" id="abstract1">
                {% if s.talk_abstract %}{{ s.talk_abstract }}{% else %}Abstract TBD{% endif %}
                </div> -->
            </td>
            <td>{{ n }}</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td>09:40</td>
            <td>Contributed talk</td>
            <td>TBD</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td>09:50</td>
            <td>Contributed talk</td>
            <td>TBD</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td>10:00</td>
            <td>
            {% assign n = "Jesse Snedeker" %}
            {% assign s = site.data.speakers | find:"name", n %}
            Invited talk: {% if s.talk_title %}"{{ s.talk_title }}"{% else %}TBD{% endif %}
            {% if s.talk_abstract %}<br><br><p style="font-size:0.75rem;">{{ s.talk_abstract }}</p>{% else %}{% endif %}
            <!-- Invited talk: {% if s.talk_title %}"{{ s.talk_title }}"{% else %}TBD{% endif %}
                <br><button class="btn-primary btn-sm" style="margin-top:0.75rem;margin-bottom:0.75rem;" onclick="toggle_visibility('abstract2')">Abstract</button>
                <div style="font-size:0.75rem;display:none;" id="abstract2">
                {% if s.talk_abstract %}{{ s.talk_abstract }}{% else %}Abstract TBD{% endif %}
                </div> -->
            </td>
            <td>{{ n }}</td>
            <td>Zoom</td>
        </tr>
        <tr class="mingle-row">
            <td></td>
            <td>10:30</td>
            <td>Coffee break / Meet-and-greet #1</td>
            <td>-</td>
            <td>Gather</td>
        </tr>
        <tr style="font-weight:bold;">
            <td></td>
            <td>11:00</td>
            <td>Panel discussion</td>
            <td><em>Invited speakers</em></td>
            <td>Zoom</td>
        </tr>
         <tr class="mingle-row">
            <td></td>
            <td>12:00</td>
            <td>Lunch / Poster session</td>
            <td>-</td>
            <td>Gather</td>
        </tr>
        <tr class="session-row">
            <td style="text-align:center;" rowspan=5>Session 2</td>
        </tr>
        <tr>
            <td>13:30</td>
            <td>
            {% assign n = "Robert Hawkins" %}
            {% assign s = site.data.speakers | find:"name", n %}
            Invited talk: {% if s.talk_title %}"{{ s.talk_title }}"{% else %}TBD{% endif %}
            {% if s.talk_abstract %}<br><br><p style="font-size:0.75rem;">{{ s.talk_abstract }}</p>{% else %}{% endif %}
            <!-- Invited talk: {% if s.talk_title %}"{{ s.talk_title }}"{% else %}TBD{% endif %}
                <br><button class="btn-primary btn-sm" style="margin-top:0.75rem;margin-bottom:0.75rem;" onclick="toggle_visibility('abstract3')">Abstract</button>
                <div style="font-size:0.75rem;display:none;" id="abstract3">
                {% if s.talk_abstract %}{{ s.talk_abstract }}{% else %}Abstract TBD{% endif %}
                </div> -->
            </td>
            <td>{{ n }}</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td>14:00</td>
            <td>Contributed talk</td>
            <td>TBD</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td>14:10</td>
            <td>Contributed talk</td>
            <td>TBD</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td>14:20</td>
            <td>
            {% assign n = "Marieke Woensdregt" %}
            {% assign s = site.data.speakers | find:"name", n %}
            Invited talk: {% if s.talk_title %}"{{ s.talk_title }}"{% else %}TBD{% endif %}
            {% if s.talk_abstract %}<br><br><p style="font-size:0.75rem;">{{ s.talk_abstract }}</p>{% else %}{% endif %}
            <!-- Invited talk: {% if s.talk_title %}"{{ s.talk_title }}"{% else %}TBD{% endif %}
                <br><button class="btn-primary btn-sm" style="margin-top:0.75rem;margin-bottom:0.75rem;" onclick="toggle_visibility('abstract4')">Abstract</button>
                <div style="font-size:0.75rem;display:none;" id="abstract4">
                {% if s.talk_abstract %}{{ s.talk_abstract }}{% else %}Abstract TBD{% endif %}
                </div> -->
            </td>
            <td>{{ n }}</td>
            <td>Zoom</td>
        </tr>
        <tr class="mingle-row">
            <td></td>
            <td>14:50</td>
            <td>Coffee break / Meet-and-greet #2</td>
            <td>-</td>
            <td>Gather</td>
        </tr>
        <tr class="session-row">
            <td style="text-align:center;" rowspan=5>Session 3</td>
        </tr>
        <tr>
            <td>15:20</td>
            <td>
            {% assign n = "Raquel Fernández" %}
            {% assign s = site.data.speakers | find:"name", n %}
            Invited talk: {% if s.talk_title %}"{{ s.talk_title }}"{% else %}TBD{% endif %}
            {% if s.talk_abstract %}<br><br><p style="font-size:0.75rem;">{{ s.talk_abstract }}</p>{% else %}{% endif %}
            </td>
            <td>{{ n }}</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td>15:50</td>
            <td>Contributed talk</td>
            <td>TBD</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td>16:00</td>
            <td>Contributed talk</td>
            <td>TBD</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td>16:10</td>
            <td>
            {% assign n = "Dan Klein" %}
            {% assign s = site.data.speakers | find:"name", n %}
            Invited talk: {% if s.talk_title %}"{{ s.talk_title }}"{% else %}TBD{% endif %}
            {% if s.talk_abstract %}<br><br><p style="font-size:0.75rem;">{{ s.talk_abstract }}</p>{% else %}{% endif %}
            <!-- Invited talk: {% if s.talk_title %}"{{ s.talk_title }}"{% else %}TBD{% endif %}
                <br><button class="btn-primary btn-sm" style="margin-top:0.75rem;margin-bottom:0.75rem;" onclick="toggle_visibility('abstract6')">Abstract</button>
                <div style="font-size:0.75rem;display:none;" id="abstract6">
                {% if s.talk_abstract %}{{ s.talk_abstract }}{% else %}Abstract TBD{% endif %}
                </div> -->
            </td>
            <td>{{ n }}</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td></td>
            <td>16:40</td>
            <td>Closing remarks</td>
            <td><em>Organizers</em></td>
            <td>Zoom</td>
        </tr>
        <tr class="mingle-row">
            <td></td>
            <td>16:45</td>
            <td>Mingling / Optional poster session</td>
            <td>-</td>
            <td>Gather</td>
        </tr>
    </tbody>
</table>

<!-- <table class="styled-table">
    <thead>
        <tr>
            <th></th>
            <th>Time</th>
            <th>Event</th>
            <th>Platform</th>
        </tr>
    </thead>
    <tbody>
        <tr class="mingle-row">
            <td></td>
            <td>08:40</td>
            <td>Poster preview</td>
            <td>Gather</td>
        </tr>
        <tr>
            <td></td>
            <td>08:55</td>
            <td>Opening remarks</td>
            <td>Zoom</td>
        </tr>
        <tr class="session-row">
            <td rowspan=5>Session 1</td>
        </tr>
        <tr>
            <td>09:00</td>
            <td>Invited talk #1</td>
            <td></td>
        </tr>
        <tr>
            <td>09:30</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>09:40</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>09:50</td>
            <td>Invited talk #2</td>
            <td></td>
        </tr>
        <tr class="mingle-row">
            <td></td>
            <td>10:30</td>
            <td>Coffee break / Meet-and-greet #1</td>
            <td>Gather</td>
        </tr>
        <tr class="session-row">
            <td rowspan=5>Session 2</td>
        </tr>
        <tr>
            <td>11:00</td>
            <td>Invited talk #3</td>
            <td></td>
        </tr>
        <tr>
            <td>11:30</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>11:40</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>11:50</td>
            <td>Invited talk #4</td>
            <td></td>
        </tr>
        <tr class="mingle-row">
            <td></td>
            <td>12:20</td>
            <td>Lunch & Poster session</td>
            <td>Gather</td>
        </tr>
        <tr class="session-row">
            <td rowspan=5>Session 3</td>
        </tr>
        <tr>
            <td>14:00</td>
            <td>Invited talk #5</td>
            <td></td>
        </tr>
        <tr>
            <td>14:30</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>14:40</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>14:50</td>
            <td>Invited talk #6</td>
            <td></td>
        </tr>
        <tr class="mingle-row">
            <td></td>
            <td>15:20</td>
            <td>Coffee break / Meet-and-greet #2</td>
            <td>Gather</td>
        </tr>
        <tr>
            <td></td>
            <td>15:50</td>
            <td>Panel discussion: invited speakers</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td></td>
            <td>16:55</td>
            <td>Closing remarks</td>
            <td>Zoom</td>
        </tr>
    </tbody>
</table> -->

<!-- <table class="styled-table">
    <thead>
        <tr>
            <th></th>
            <th>Time</th>
            <th>Event</th>
            <th>Platform</th>
        </tr>
    </thead>
    <tbody>
        <tr class="mingle-row">
            <td></td>
            <td>08:40</td>
            <td>Poster preview / mingling</td>
            <td>Gather</td>
        </tr>
        <tr>
            <td></td>
            <td>08:55</td>
            <td>Opening remarks</td>
            <td>Zoom</td>
        </tr>
        <tr class="session-row">
            <td rowspan=6>Session 1</td>
        </tr>
        <tr>
            <td>09:00</td>
            <td>Invited talk 1</td>
            <td></td>
        </tr>
        <tr>
            <td>09:30</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>09:40</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>09:50</td>
            <td>Invited talk 2</td>
            <td></td>
        </tr>
        <tr>
            <td>10:20</td>
            <td>Q&A</td>
            <td></td>
        </tr>
        <tr class="mingle-row">
            <td></td>
            <td>10:30</td>
            <td>Coffee / mingling</td>
            <td>Gather</td>
        </tr>
        <tr class="session-row">
            <td rowspan=6>Session 2</td>
        </tr>
        <tr>
            <td>10:45</td>
            <td>Invited talk 3</td>
            <td></td>
        </tr>
        <tr>
            <td>11:15</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>11:25</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>11:35</td>
            <td>Invited talk 4</td>
            <td></td>
        </tr>
        <tr>
            <td>12:05</td>
            <td>Q&A</td>
            <td></td>
        </tr>
        <tr class="mingle-row">
            <td></td>
            <td>12:15</td>
            <td>Lunch & Poster session</td>
            <td>Gather</td>
        </tr>
        <tr class="session-row">
            <td rowspan=6>Session 3</td>
        </tr>
        <tr>
            <td>14:00</td>
            <td>Invited talk 5</td>
            <td></td>
        </tr>
        <tr>
            <td>14:30</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>14:40</td>
            <td>Contributed talk</td>
            <td></td>
        </tr>
        <tr>
            <td>14:50</td>
            <td>Invited talk 6</td>
            <td></td>
        </tr>
        <tr>
            <td>15:20</td>
            <td>Q&A</td>
            <td></td>
        </tr>
        <tr class="mingle-row">
            <td></td>
            <td>15:30</td>
            <td>Coffee / mingling</td>
            <td>Gather</td>
        </tr>
        <tr>
            <td></td>
            <td>15:45</td>
            <td>Panel discussion: invited speakers</td>
            <td>Zoom</td>
        </tr>
        <tr>
            <td></td>
            <td>16:55</td>
            <td>Closing remarks</td>
            <td>Zoom</td>
        </tr>
    </tbody>
</table> -->


<!-- The main categories (or tracks) of the different talks as well as their coloring can be adapted in the `_config.yml` file under `conference.talks.main_categories`. See also the [Talk Settings](https://github.com/DigitaleGesellschaft/jekyll-theme-conference/#talk-settings-main-categories) section of the theme's README file. -->