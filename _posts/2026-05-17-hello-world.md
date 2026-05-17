---
layout: default
title: "Hello World: My First Post"
date: 2026-05-17 00:01:00 +0000
---

<h1>{{ page.title }}</h1>
<p class="text-muted">{{ page.date | date: "%B %d, %Y" }}</p>

<div class="post-content mt-4">
    <p>Welcome to my new blog! This is where I'll be sharing my thoughts on mathematics, software engineering, and music.</p>
    
    <p>I've recently refactored this website to use Jekyll and a custom "Hacker" aesthetic. I'm excited to have a dedicated space to document my learning journey.</p>
    
    <p>Stay tuned for more updates!</p>
</div>

<a href="{{ '/blogs.html' | relative_url }}" class="btn btn-outline-beige mt-5">← Back to Blogs</a>
