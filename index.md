---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
# Serving

{% highlight powershell %}
docker run --rm --volume="${PWD}:/srv/jekyll" --volume="${PWD}/_vendor/bundle:/usr/local/bundle" -p 4000:4000 -it jekyll/jekyll:3.3 jekyll serve
{% endhighlight %}
