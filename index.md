---
layout: minimal
title: Math 290
nav_exclude: true
seo:
  type: Course
  name: Virtual quantum many-body seminar, 2020 Fall to 2021 Summer
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }


<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script type="text/javascript" src="https://cdn.rawgit.com/mrvautin/typewrite/master/dist/typewrite.min.js"></script>
<script>
    $(document).ready(function(){
        $('#typewriteText').typewrite({
            continuous: true,
            actions: [
                {type: 'hello! '},
                {type: '<br>'},
                {type: 'weclome '},
                {delay: 1500},
                {remove: {num: 1, type: 'stepped'}},
                {select: {from: 11, to: 16}},
                {delay: 2000},
                {remove: {num: 5, type: 'whole'}},
                {delay: 300},
                {type: 'lcome to `math 290`! '},
                {type: '<br>'},
                {type: 'we study '},
                {type: 'DMET'},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'QLSP'},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'DMFT'},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'LCU'},
                {delay: 4500},
                {remove: {num: 3, type: 'stepped'}},
                {type: 'QSP'},
                {delay: 4500},
                {remove: {num: 3, type: 'stepped'}},
                {type: 'QAOA'},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'AQC'},
                {delay: 4500},
                {remove: {num: 3, type: 'stepped'}},
                {type: 'VTAA'},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'HHL'},
                {delay: 4500},
                {remove: {num: 3, type: 'stepped'}},
                {type: 'CCSD'},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'quantum!'},
                {delay: 60000},
            ]
        });
    });
</script>

<div id="typewriteText"></div>


- **When**: 🕒 Fridays 10AM-12PM
- **Where**: 💻 Zoom. 
- Please send me an email (linlin at math dot berkeley dot edu) - to ask for the zoom id.
- **Moderator**: Jiahao Yao

{% for module in site.modules %}
{{ module }}
{% endfor %}
