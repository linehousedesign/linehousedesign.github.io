---
layout: page
title: Feed
permalink: /insta-grid/
banner: /assets/images/main-site-images/footer-news.jpg

---
{% raw %}
<script type="text/javascript" src="/assets/js/instafeed.min.js"></script>
<script type="text/javascript">
    var userFeed = new Instafeed({
        get: 'user',
        userId: 1040736,
        accessToken: '1040736.63c22ba.2a19f6fe5ec94511998b2f554c18e3bb',
        resolution: 'low_resolution',
        template: '<div class="insta-container"><div class="image-box"><a href="{{link}}"><img src="{{image}}" /></a></div><div class="info-box">Here comess some words about what we have been up to recently {{caption}}</div></div>'
    });
    userFeed.run();
</script>
{% endraw %}
<div class="insta-grid-page" id="instafeed">
</div>
