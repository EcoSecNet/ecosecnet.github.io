+++
sort_by = "date"
template = "pages.html"
+++

<figure class="lab-banner"><img src="../images/coda-banner.jpg" width="1600" height="533" alt="The CODA building, which houses Georgia Tech's School of Cybersecurity and Privacy and our lab."/></figure>

<div class="fr lab-mark">
<img src="../images/lab-mark.svg" width="152" height="136" alt="Our lab's logo."/>
<div class="lab-social">{{ social() }}</div>
</div>

**About.**
At the Economics & Security Lab, we like breaking things: pushing systems to their limits and understanding how they fail is fundamental to making them robust.
This drives our research into the economics and security of distributed systems and AI at Georgia Tech.

**Hiring.**
We are hiring students at all levels, and are also open to interns.
<a href="mailto:lab@ecosec.net?subject=Joining%20EcoSec%20Lab&body=Hi%2C%20my%20name%20is%20...%2C%20my%20CV%20is%20attached.%20I%27d%20like%20to%20join%20the%20lab%20because%20...">Get in touch!</a>

<hr style="height:1px; visibility:hidden; padding-bottom:1%;">

{{ records(data_path="data/news.toml") }}

## Members.

{{ members() }}

{{ records(data_path="data/seminars.toml") }}

{{ records(data_path="data/courses.toml") }}

{{ records(data_path="data/papers.toml") }}

{{ records(data_path="data/media.toml") }}