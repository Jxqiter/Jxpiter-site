---
layout: default
---

<div style="display: flex; align-items: center; gap: 2rem; margin-bottom: 2rem;">
  <img src="/assets/img/me.jpg" alt="profile" style="width: 150px; border-radius: 50%; border: 2px solid #0f0;" />
  <div>
    <h2>Hello, I'm <strong>jxpiter</strong></h2>
    <p>
      I'm a cybersecurity enthusiast passionate about reverse engineering, digital forensics, and defending systems.<br>
      I explore the dark corners of code to understand how things break — and how to fix them.
    </p>
  </div>
</div>

---

### 🧠 Latest Posts

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small> — {{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
