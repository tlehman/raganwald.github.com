---
---

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN">

<html lang="en">

<head> <meta http-equiv="Content-Type" content="text/html; charset=utf-8"> <title>raganwald</title> <meta name="author" content="Reginald Braithwaite"> <link rel="openid.server" href="http://www.myopenid.com/server " /> <link rel="openid.delegate" href="http://reginald.braithwaite.myopenid.com/" /> <meta http-equiv="X-XRDS-Location" content="http://reginald.braithwaite.myopenid.com/xrds" />

<style> body { margin-top: 0px; margin-left: 20px; width: 600px; font-family:trebuchet ms, verdana, sans-serif; background-color:white; } p.copy { margin-bottom: 10px; } p.heading { font-weight: bolder; margin-top: 20px; margin-bottom: 5px; } p.title { text-align: right; font-weight: bolder; margin-bottom: 20px; } </style>

</head>

<body>

<p class="heading">raganwald</p>

<p class="copy">There isn't anything here. You are may be interested in:</p>

<p class="copy"></p>

<ul>
  <li class="copy"><a href="http://braythwayt.com">braythwayt.com</a>, my personal home page.
  </li>
  <li class="copy"><a href="http://leanpub.com/u/raganwald">leanpub.com/u/raganwald</a>, my books.
  </li>
  <li class="copy"><a href="http://github.com/raganwald">github.com/raganwald</a>, my active code repositories.
  </li>
  <li class="copy"><a href="http://twitter.com/raganwald">@raganwald</a>, my twitter feed.
  </li>
  <li class="copy"><a href="mailto:reg@braythwayt.com">reg@braythwayt.com</a>, my email address.
  </li>
</ul>

<p class="heading">new blog</p>

<p class="copy"></p>
<p class="copy">I am writing a new blog. Here are the most recent posts:</p>
<p class="copy"></p>

<div class="related">
  <ul>
    {% for post in site.posts %}
    <li>
<span>{{ post.date | date: "%B %e, %Y" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
  </ul>
</div>

<p class="copy"></p>

<p class="copy">Thanks for stopping by,</p>

<p class="copy"></p>

<p class="copy"><a href="http://braythwayt.com">Reginald <em>raganwald</em> Braithwaite</a></p>

</body> </html>