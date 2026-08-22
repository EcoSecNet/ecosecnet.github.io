+++
sort_by = "date"
template = "pages.html"
+++

<figure class="lab-banner"><img src="../images/coda-banner.jpg" width="1600" height="533" alt="The CODA building at Georgia Tech."/></figure>

<div class="fr lab-mark">
<img src="../images/lab-mark.svg" width="152" height="136" alt="The Economics & Security Lab mark."/>
<div class="lab-social">{{ social() }}</div>
</div>

**About.**
At the Economics & Security Lab, we like breaking things: pushing systems to their limits and understanding how they fail is fundamental to making them robust.
This drives our research into the economics and security of distributed systems and AI at Georgia Tech.

**Hiring.**
We are hiring students at all levels, and are also open to interns.
Do get in touch if you want to collaborate or chat!


<hr style="height:1px; visibility:hidden; padding-bottom:1%;">


{{ records(data_path="data/news.toml") }}

## Members.

{{ members() }}

{{ records(data_path="data/seminars.toml") }}

{{ records(data_path="data/courses.toml") }}

{{ records(data_path="data/papers.toml") }}
