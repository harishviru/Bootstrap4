Bootstrap 4 Carousel 
--------------------
  .carousel
  .slide
   data-ride="carousel"

  .carousel-inner 
  .carousel-item
  .carousel-caption

 #Left and right controls
 .carousel-control-prev  
  data-slide="prev"
 .carousel-control-prev-icon

 .carousel-control-next
  data-slide="next"
 .carousel-control-next-icon

 #indicators 
 .carousel-indicators
  data-target="#id"
  data-slide-to="0/1/2.."
  .active

$('.carousel').carousel({
  interval: 2000,
   pause :'hover'
})
ride,wrap,keyboard [value=true/false]
#Events

slide.bs.carousel	This event fires immediately when the slide instance method is invoked.
slid.bs.carousel	This event is fired when the carousel has completed its slide transition.