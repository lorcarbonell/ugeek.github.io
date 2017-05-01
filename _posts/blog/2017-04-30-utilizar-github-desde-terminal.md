---
layout: page
title: "Como utilizar GitHub en la Terminal"
date: 2017-04-30
tags: [github, blog, terminal]
categories: github
---
#### Publicado por Angel

Hoy he empezado a utilizar GitHub desde la Terminal. Hasta ahora lo hacia desde la propia interfaz web y he de decir que no hay ni punto de comparación.  

Utilizar la terminal es muchísimo más rápido tanto el poder previsulizar el blog en local, como el subir las modificaciones una vez testeadas en local, a GitHub.  

Como siempre os he comentado, utilizar la terminal al principio impresiona, pero hay que reconocer que no hay herramienta más productiva y potente que esta.  

Os dejo estas 2 publicaciones de dos buenos amigos, [inclusa](http://inclusa.github.io/2016/03/30/GIT-Principals-comandaments-que-utilitze.html) y [sasogu](https://sasogu.github.io/2017/04/29/github.html), que me han ayudado a poder llevar todo esto a cabo y os ayudaran gracias a esta webs, a conocer muchísimo mejor los comandos a utilizar en la terminal para GitHub.




<!-- -------------------------------------Aquí abajo los comentarios -------------------------------------------  -->
Tags: {% assign sorted_tags = page.tags | sort %} {% for tag in sorted_tags %} , <span class="tag"><a href="/tag#{{ tag }}">{{ tag }}</a></span> {% endfor %},


{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://https-angelbcn-github-io-ugeek.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

{% endif %}

<script id="dsq-count-scr" src="//https-angelbcn-github-io-ugeek.disqus.com/count.js" async></script>