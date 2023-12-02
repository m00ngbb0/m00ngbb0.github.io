---
layout: project
title: Address Book
excerpt: "A simple address book project"
comments: false
---

<!DOCTYPE html>
<html class="no-js">
<head>
   {% include head.html %}
</head>
<body>
   {% include nav.html %}
   <header class="header" role="banner">
      <div class="wrapper animated fadeIn">
         <div class="content">
            <div class="post-title">
               <h1>{{ page.title }}</h1>
               <a class="btn zoombtn" href="{{site.url}}/projects/">
                  <i class="fa fa-chevron-left"></i>
               </a>
            </div>
            <p>test</p> <!-- "test" 라는 글자만 나타날 부분 -->
         </div>
      </div>
   </header>
   {% include scripts.html %}
</body>
</html>