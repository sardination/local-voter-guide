---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
{%- for data_page in site.candidate_data -%}
    <li><a href="{{ data_page.url | relative_url }}">{{ data_page.title }}</a></li>
{%- endfor -%}