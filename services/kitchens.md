---
layout: page
title: Kitchens
permalink: /services/kitchens
navtype: drawer
hasgallery: true
---
<script>
$(window).load(function() {
  // The slider being synced must be initialized first
  $('#carousel').flexslider({
    animation: "slide",
    controlNav: false,
    animationLoop: false,
    slideshow: false,
    itemWidth: 180,
    maxItems: 4,
    itemMargin: 5,
    asNavFor: '#mainslider'
  });
  $('#mainslider').flexslider({
    animation: "slide",
    controlNav: false,
    animationLoop: false,
    slideshow: false,
    sync: "#carousel",
    smoothHeight: true
  });
})
</script>

<div style="padding: 0 100px;">

<div id="mainslider" class="flexslider">
  <ul class="slides">
    <li>
      <img src="/images/windoors.jpg" />
      <p class="flex-caption">Caption</p>
    </li>
    <li>
      <img src="/images/kitchens.jpg" />
      <p class="flex-caption">Caption</p>
    </li>
    <li>
      <img src="/images/bathrooms.jpg" />
      <p class="flex-caption">Caption</p>
    </li>
    <li>
      <img src="/images/basements.jpg" />
      <p class="flex-caption">Caption</p>
    </li>
    <li>
	<img src="/images/general.jpg" alt="">
	<p class="flex-caption">Caption</p>
    </li>
  </ul>
</div>

<div id="carousel" class="flexslider">
  <ul class="slides">
    <li>
      <img src="/images/windoors-thumb.jpg" />
    </li>
    <li>
      <img src="/images/kitchens-thumb.jpg" />
    </li>
    <li>
      <img src="/images/bathrooms-thumb.jpg" />
    </li>
    <li>
      <img src="/images/basements-thumb.jpg" />
    </li>
    <li>
      <img src="/images/general-thumb.jpg" />
    </li>
  </ul>
</div>

</div>