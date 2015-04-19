---
layout: page
title: Press
permalink: /press/
banner: /assets/images/main-site-images/footer-news.jpg
presslinks: 
  -  name: Ehousing Magazine, Lone Ranger, March 2015
     image: /assets/images/press/ehousing-lone-ranger-001.jpg
     url: /assets/images/press/ehousing-lone-ranger.pdf
     name: BOB Magazine, Lone Ranger, February 2015
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
      <p><a href="{{ presslink.image }}" data-lightbox="lightbox-galery" data-title="{{ presslink.name }}<br /><a style='color: #CCC;' href='{{ presslink.url }}' target='_blank'>Link to full article</a>"><img width="100%" src="{{ presslink.image }}" alt="{{ presslink.name }}" title="{{ presslink.name }}" /></a></p>
		</div>
		<div class="info-box">
			<!-- p><a href="{{ presslink.url }}">{{ presslink.name }}</a></p> -->
		</div>
	</div>
  {% endfor %}
</div>