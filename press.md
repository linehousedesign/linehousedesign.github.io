---
layout: page
title: Press
permalink: /press/
banner: /assets/images/main-site-images/footer-news.jpg
presslinks:
  -  name: Interiors, Shenzhen Deli, May 2015
     image: /assets/images/press/interiors-deli-shenzhen-001.jpg
  -  name: Interiors, Shenzhen Deli, May 2015
     image: /assets/images/press/interiors-deli-shenzhen-002.jpg
  -  name: Interiors, Shenzhen Deli, May 2015
     image: /assets/images/press/interiors-deli-shenzhen-003.jpg
  -  name: Interiors, Shenzhen Deli, May 2015
     image: /assets/images/press/interiors-deli-shenzhen-004.jpg
  -  name: Interiors, Shenzhen Deli, May 2015
     image: /assets/images/press/interiors-deli-shenzhen-005.jpg
  -  name: CityWeekend, Factory Five, Summer 2015
     image: /assets/images/press/cityweekend-factory-five.jpg
  -  name: NYARUM, Lone Ranger, Summer 2015
     image: /assets/images/press/nya-rum-lone-ranger-001.jpg
  -  name: NYARUM, Lone Ranger, Summer 2015
     image: /assets/images/press/nya-rum-lone-ranger-002.jpg
  -  name: NYARUM, Lone Ranger, Summer 2015
     image: /assets/images/press/nya-rum-lone-ranger-003.jpg
  -  name: INDESIGNLIVE, May 2015
     image: /assets/images/press/indesign_live_hk.jpg
     url: http://www.indesignlive.hk/articles/people/linehouse-design-poetry-and-pragmatism
  -  name: AD Germany, Shenzhen Deli, May 2015
     image: /assets/images/press/ad_germany_may_2015_002.jpg
  -  name: AD Germany, Shenzhen Deli, May 2015
     image: /assets/images/press/ad_germany_may_2015_001.jpg
  -  name: Design Boom, Little Catch, May 2015
     image: /assets/images/press/design-boom-little-catch.jpg
     url: http://www.designboom.com/architecture/linehouse-little-catch-shanghai-05-05-2015/
  -  name: Dezeen, Little Catch, May 2015
     image: /assets/images/press/dezeen_little_catch.jpg
     url: http://www.dezeen.com/2015/05/03/little-catch-fishmonger-in-shanghai-is-lined-with-a-metal-frame-net/
  -  name: Elle Decor, Factory Five, May 2015
     image: /assets/images/press/elle-decor-factory-five-5-may-2015.jpg
     url: http://www.elledecor.it/interior-decoration/Linehouse-bike-shop-multifunzione-stile-industriale-shanghai
  -  name: Modern Weekly, Factory Five, April 2015
     image: /assets/images/press/modern-weekly-11-april-2015.jpg
  -  name: L'officiel Magazine, Factory Five
     image: /assets/images/press/linehouse-lofficiel.jpg
  -  name: Ehousing Magazine, Lone Ranger, March 2015
     image: /assets/images/press/ehousing-lone-ranger-001.jpg
     url: /assets/images/press/ehousing-lone-ranger.pdf
  -  name: BOB Magazine, Lone Ranger, February 2015
     image: /assets/images/press/bob-magazine-cover.jpg
     url: /assets/images/press/2015_2_bob-magazine.pdf
  -  name: Elle Decor, Lone Ranger
     image: /assets/images/press/elle-decor-lone-range.jpg
     url: http://www.elledecor.it/interior-decoration/lone-ranger-ristorante-hot-dog-shanghai-interni-design
  -  name: Archilovers, Lone Ranger
     image: /assets/images/press/archilovers-lone-ranger.jpg
     url: http://www.archilovers.com/projects/148987/lone-ranger-hot-dog-shop.html
  -  name: Design Boom, Lone Ranger
     image: /assets/images/press/design-boom-lone-ranger.jpg
     url: http://www.designboom.com/architecture/linehouse-lone-ranger-hot-dog-shop-shanghai-china-02-11-2015/
  -  name: Wallpaper, Factory Five
     image: /assets/images/press/wallpaper-factory-five.jpg
     url: http://www.wallpaper.com/travel-directory/china/shanghai/shops/factory-five/605
  -  name: Arch Daily, Lone Ranger
     image: /assets/images/press/arch-daily-lone-ranger.jpg
     url: http://www.archdaily.com/598150/lone-ranger-hot-dog-shop-linehouse/
  -  name: Wallpaper, Lone Ranger
     image: /assets/images/press/wallpaper-lone-ranger.jpg
     url: http://www.wallpaper.com/travel-directory/china/shanghai/restaurants/lone-ranger/587
  -  name: Elle Decor, Shenzhen Deli
     image: /assets/images/press/elle-decor-shenzhen.jpg
     url: http://www.elledecor.it/interior-decoration/deli-pasticceria-shenzhen-interni-design
  -  name: The Coolist, Factory Five
     image: /assets/images/press/the-coolist-factory-five.jpg
     url: http://www.thecoolist.com/factory-five-bike-shop-shanghai-linehouse-architecture/
  -  name: Design Boom, Factory Five
     image: /assets/images/press/design-boom-factory-five.jpg
     url: http://www.designboom.com/architecture/factory-5-bikes-jingan-linehouse-02-27-2015/
  -  name: Dezeen, Shenzhen Deli
     image: /assets/images/press/dezeen-deli-shenzhen.jpg
     url: http://www.dezeen.com/2014/06/06/brass-cage-like-structure-inserted-into-shenzhen-patisserie-by-linehouse/
  -  name: Archilovers, Factory Five
     image: /assets/images/press/archilovers-factory-five.jpg
     url: http://www.archilovers.com/projects/150296/factory-5-bike-shop.html
---

<div class="news-grid-page">
  {% for presslink in page.presslinks %}
	<div class="news-container">
		<div class="image-box">
      <p><a href="{{ presslink.image }}" data-lightbox="lightbox-galery" data-title="{{ presslink.name }}<br />
        {% if presslink.url %}
          <a style='color: #CCC;' href='{{ presslink.url }}' target='_blank'>Link to full article</a>{% endif %}
          ">
        <img width="100%" src="{{ presslink.image }}" alt="{{ presslink.name }}" title="{{ presslink.name }}" /></a></p>
		</div>
		<div class="info-box">
			<!-- p><a href="{{ presslink.url }}">{{ presslink.name }}</a></p> -->
		</div>
	</div>
  {% endfor %}
</div>