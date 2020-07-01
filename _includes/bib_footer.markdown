## References

{% bibliography --cited %}

## Share / cite / discuss this post

{% if page.share %}{% include social-share.html %}{% endif %} 

{% assign num = page.url | size | minus: 1 %}
{% assign citekey = page.url | replace: "/", "_" | slice: 0, num %}

<div class="bibtex" style="display:none;" id='{{ postCite }}'>
<pre>
@misc{Rogers{{ citekey }},
  title = { {{ page.title }}},
  journal = {Hacking Semantics},
  url = { https://hackingsemantics.xyz{{page.url}} },
  author = {Rogers, Anna},
  day = { {{page.date | date: "%d"}} },
  month = { {{page.date | date: "%b"}} },
  year = { {{ page.date | date: "%Y" }} }
}
</pre>
</div>