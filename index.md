---
layout: default
title: Home
---
<div class="md:col-span-4 md:col-start-3 col-start-0 col-span-6">
  <div class="mb-4">
    <h1 class="text-2xl md:text-4xl font-bold mb-2">KO-KE Creative Farm</h1>
    {% for item in site.data.footer.description %}
    <p class="text-xl md:text-2xl">{{ item.text }}</p>
    {% endfor %}
  </div>
  
  <div class="mb-4">
    <p class="text-xl">Follow us on Instagram: <a href="https://instagram.com/{{ site.data.footer.social.instagram }}" class="underline">@{{ site.data.footer.social.instagram }}</a></p>
    <p class="text-xl">Contact: <a href="mailto:hello@ko-ke.net" class="underline">hello@ko-ke.net</a></p>
  </div>
</div>