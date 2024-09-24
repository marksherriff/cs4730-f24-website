---
layout: default
title: Schedule
nav_order: 3
---

# Course Schedule

<table class="schedtab"><thead>
<tr>
    <th>Date</th>
    <th>Topic</th>
    <th>Reading</th>
    <th>Due Dates</th>
    </tr>
    </thead>
    <tbody>
{% for day in site.data.lectureschedule %}
{% if day.type == 'holiday' %}
<tr class="holiday">
{% elsif day.type == 'quiz' %}
<tr class="quiz">
{% else %}
<tr>
{% endif %}
<td class="text-center sched">{{day.date}}</td>
<td class="sched">
{% if day.coursepack %}
<a href="{{day.coursepack}}">
{% endif %}
{{day.topic}}
{% if day.coursepack %}
    </a>
{% endif %}
{% if day.topic2 %}
&
{% if day.coursepack2 %}
<a href="{{day.coursepack2}}">
{% endif %}
{{day.topic2}}
{% if day.coursepack2 %}
    </a>
{% endif %}
{% endif %}
</td>
<td class="sched">
{% if day.reading %}
{% if day.readinglink %}
<a href="{{day.readinglink}}">
{% endif %}
{{day.reading}}
{% else %}
&nbsp;
{% endif %}
{% if day.readinglink %}
</a>
{% endif %}
</td>
<td class="sched">
{% if day.due %}
{% if day.due_link%}
<a href="{{day.due_link}}">
{% endif %}
{{day.due}}
{% if day.due_link%}
</a>
{% endif %}
{% endif %}
{% if day.due2 %}
<br>
{% if day.due_link2%}
<a href="{{day.due_link2}}">
{% endif %}
{{day.due2}}
{% if day.due_link2%}
</a>
{% endif %}
{% endif %}
</td>
</tr>
{% endfor %}
</tbody></table>