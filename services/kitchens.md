---
layout: page
title: Kitchens
permalink: /services/kitchens/
navtype: drawer
hasgallery: true
---
<script>
$(window).load(function() {
  // The slider being synced must be initialized first
  $('#carousel').flexslider({
    animation: "slide",
    controlNav: false,
    animationLoop: true,
    slideshow: false,
    itemWidth: 180,
    maxItems: 4,
    itemMargin: 5,
    asNavFor: '#mainslider'
  });
  $('#mainslider').flexslider({
    animation: "slide",
    controlNav: false,
    animationLoop: true,
    slideshow: false,
    sync: "#carousel",
    smoothHeight: true
  });
})
</script>

<div class="flexslider-container">

<div id="mainslider" class="flexslider">
  <ul class="slides">
    <li>
      <img src="/images/windoors.jpg" />
      <p class="flex-caption">These are some windows.</p>
    </li>
    <li>
      <img src="/images/kitchens.jpg" />
      <p class="flex-caption">Behold, a picture of a kitchen.</p>
    </li>
    <li>
      <img src="/images/bathrooms.jpg" />
      <p class="flex-caption">You can't bring that camera in here.</p>
    </li>
    <li>
      <img src="/images/basements.jpg" />
      <p class="flex-caption">Basements are the new garages, nawmean?</p>
    </li>
    <li>
	<img src="/images/general.jpg" alt="">
	<p class="flex-caption">General is the new specific. Oh, by the way, these descriptions can be more than one line long.</p>
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