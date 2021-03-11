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

<!-- Place this tag in your head or just before your close body tag. -->
<script async defer src="https://buttons.github.io/buttons.js"></script>

<!-- Place this tag where you want the button to render. -->
<a class="github-button" href="https://github.com/lin-lin/2020To2021_290" data-icon="octicon-star" aria-label="Star lin-lin/2020To2021_290 on GitHub">Star</a>

<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script type="text/javascript" src="https://cdn.rawgit.com/mrvautin/typewrite/master/dist/typewrite.min.js"></script>
<script>
    $(document).ready(function(){
        $('#typewriteText').typewrite({
            selectedBackground: '#7253ed',
            selectedText: '#FFFFFF',
            continuous: true,
            actions: [
                {type: 'hello! '},
                {type: '<br>'},
                {type: 'weclome '},
                {delay: 1500},
                {remove: {num: 1, type: 'stepped'}},
                {select: {from: 12, to: 17}},
                {delay: 2000},
                {remove: {num: 5, type: 'whole'}},
                {delay: 300},
                {type: 'lcome to `math 290`! '},
                {type: '<br>'},
                {type: 'we study '},
                {type: 'DMET'},
                {select: {from: 45, to: 49}},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'QLSP'},
                {select: {from: 45, to: 49}},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'DMFT'},
                {select: {from: 45, to: 49}},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'LCU'},
                {select: {from: 45, to: 48}},
                {delay: 4500},
                {remove: {num: 3, type: 'stepped'}},
                {type: 'QSP'},
                {select: {from: 45, to: 48}},
                {delay: 4500},
                {remove: {num: 3, type: 'stepped'}},
                {type: 'QAOA'},
                {select: {from: 45, to: 49}},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'AQC'},
                {select: {from: 45, to: 48}},
                {delay: 4500},
                {remove: {num: 3, type: 'stepped'}},
                {type: 'VTAA'},
                {select: {from: 45, to: 49}},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'HHL'},
                {select: {from: 45, to: 48}},
                {delay: 4500},
                {remove: {num: 3, type: 'stepped'}},
                {type: 'CCSD'},
                {select: {from: 45, to: 49}},
                {delay: 4500},
                {remove: {num: 4, type: 'stepped'}},
                {type: 'quantum!'},
                {delay: 60000},
            ]
        });
    });
</script>

<div id="typewriteText"></div>

<style>
  .one {
    position: relative;
  }

  .two {
    position: absolute;
    transition: opacity .2s ease-in-out;
    -moz-transition: opacity .2s ease-in-out;
    -webkit-transition: opacity .2s ease-in-out;
  }
</style>

<div onmouseout="logo_stop()" onmouseover="logo_start()">
  <div class="one">
    <div class="two" id='logo_image'><img src='./figures/group_logo_after.png?sanitize=true&raw=true'></div>
    <img src='./figures/group_logo.png?sanitize=true&raw=true'>
  </div>
  <script type="text/javascript">
    function logo_start() {
      document.getElementById('logo_image').style.opacity = "1";
    }
    function logo_stop() {
      document.getElementById('logo_image').style.opacity = "0";
    }
    logo_stop()
  </script>
  <p align="center">
  <em><small>Designed by <a href='https://math.berkeley.edu/~difang/'>Di Fang</a></small></em>
  </p>
</div>

- **When**: 🕒 Fridays 10AM-12PM
- **Where**: 💻 Zoom. 
- Please send me an email (linlin at math dot berkeley dot edu) - to ask for the zoom id.
- **Moderator**: Jiahao Yao


{% for module in site.modules %}
{{ module }}
{% endfor %}
