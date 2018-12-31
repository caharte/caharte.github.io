# Welcome

## This is a test of the github pages jeckyll setup

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

### subsubheading

```
some code
```

**bold**

*italic*


* this is a list
* bullets

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Back to c8051 development after a while away. Props to <a href="https://twitter.com/siliconlabs?ref_src=twsrc%5Etfw">@siliconlabs</a>, Simplicity Studio really is very easy to set up and get going on mac :)</p>&mdash; Chris Harte (@MelodientUK) <a href="https://twitter.com/MelodientUK/status/838715871400984576?ref_src=twsrc%5Etfw">March 6, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>



![test image](/images/platter_sensor.jpeg){:class="img-responsive"}






<form action="https://formspree.io/chris+formspree@melodient.com"
      method="POST">
    <input type="text" name="name">
    <input type="email" name="_replyto">
    <textarea name="message" placeholder="Your message"></textarea>
    <input type="hidden" name="_next" value="index.html" />
    <input type="submit" value="Send">
</form> 
