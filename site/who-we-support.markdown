---
layout: page
title: The people we support
permalink: /people-we-support/
---

Direct Support for Ukraine is working with Yuliya now.  With your donations we hope to be able to widen our support to others like her.


### YULIYA IN KYIV
<!-- todo: image -->
Caring for children and young people with special needs who cannot flee the war.

An Introduction from Nataliya

Yuliya has been supporting children and young adults with very special needs in Ukraine for several years now. Their life has always been difficult, but current war made things almost impossible (how can a single mum move a 14 year old bed ridden boy to a bomb shelter on short notice?). The other day we were having a late evening call (she had spent whole day trying to find adult nappies in different humanitarian aid centres – all to no avail) and she promised to write more about “her” children later after the conversation (I do notice the tenderness in her voice as she says "her"). Late at night, I get a brief message that there were more rockets flying by Yuliya’s house and she had to organize a sleeping space for herself and her daughter in the corridor. Next day, despite broken sleep, she sends me a long list of needs of families she supports… and now it is my turn to loose sleep… because of everything these families are going through.


I hope we can help.



## The families Yuliya supports

<br>

  {%- assign default_paths = site.pages | map: "path" -%}
  {%- assign page_paths = default_paths | where_exp:"path", "path contains 'families'" -%}
	          {%- for path in page_paths -%}
            {%- assign my_page = site.pages | where: "path", path | first -%}
            {%- if my_page.title -%}
- [{{my_page.title}}]({{my_page.url | relative_url}})<br>
            {%- endif -%}
          {%- endfor -%}
<br>


