---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
{% assign call_page = site.pages | where:"title", "Call for Participation" | first %}

<img src="{{ '/assets/images/logo.png' | relative_url }}" alt="ODAI-LIB Logo" style="max-width: 300px;">

This competition aims to address challenges arising from software ecosystem dependencies by introducing a novel approach: On-Demand Library Generation (ODAI-LIB). Instead of relying on vast, complex, and potentially vulnerable external repositories, contestants will focus on dynamically generating small, context-specific, and high-quality libraries precisely when they are needed within a project. The participants will leverage prior experience in software ecosystems and have already compiled an initial dataset of software libraries and performed preliminary comparative analyses of human-generated versus AI-generated code. 

{{ call_page.content }}