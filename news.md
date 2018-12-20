---
layout: page
title: Feed
permalink: /news/
banner: /assets/images/main-site-images/footer-news.jpg

---
{% raw %}
<script type="text/javascript" src="/assets/js/instafeed.min.js"></script>
<script type="text/javascript">
    var userFeed = new Instafeed({
        get: 'user',
        userId: 2090282915,
        limit: 100,
        filter: function(image) {
          return image.tags.indexOf('linehousenews') >= 0;
        },
        accessToken: '2090282915.03168fc.bf7e1a4cb9c7454ba95deddab0b555b0',
        resolution: 'standard_resolution',
        template: '<a href="{{link}}"><div class="news-container"><div class="image-box"><img src="{{image}}" /></div><div class="overlay"><div class="text-in-overlay"><img src="/assets/images/main-site-images/heart.png" class="insta-icon" width="19" /><span style="vertical-align: middle;">&nbsp;{{likes}}  &nbsp;&nbsp;</span><img src="/assets/images/main-site-images/comment.png" class="insta-icon" width="19" /> <span style="vertical-align: middle;"> {{comments}}</span></div></div></div></a><div class="news-container"><div class="info-box">{{caption}}</div></div><div style="clear: both;"><br /><hr><br /><br /></div></div>'
    });
    userFeed.run();
</script>
{% endraw %}
<div class="news-grid-page" id="instafeed">
</div>
<div class="news-grid-page" style="text-align: center;">
  <span class="news-button"><a href="https://www.instagram.com/line___house/">More Linehouse updates</a></span>
</div>

