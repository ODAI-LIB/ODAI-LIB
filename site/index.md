---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
{% assign call_page = site.pages | where:"title", "Call for Participation" | first %}

<img src="{{ '/assets/images/logo.jpg' | relative_url }}" alt="ODAI-LIB Logo" style="max-width: 300px;">

This competition aims to address challenges arising from software ecosystem dependencies by introducing a novel approach: On-Demand Library Generation (ODAI-LIB). 

Contestants will focus on dynamically generating high-quality libraries precisely when they are needed within a project. The participants will leverage an initial dataset of software libraries. Rather than benchmarking, participants will demonstrate practical usage in a real-world scenario using real data provided. 
 
{{ call_page.content }}
