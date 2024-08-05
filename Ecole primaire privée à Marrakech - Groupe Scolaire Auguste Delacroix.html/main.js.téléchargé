jQuery(document).ready(function ($) {

	$(".oma-menu-hover-effect").each(function(i, element) {
		var tl = new TimelineMax({paused:true, reversed:true}),
	    theText = $(this).find(".bg-meta");
	    theTitle = $(this).find(".bg-meta h2");
	    theSubMenu = $(this).find(".oma-sub-menu");
	    theLinks = $(this).find(".oma-sub-menu ul li");
		tl.to(theText, 0.5, {css:{transform:"initial", top:"10px"}}, 0);
		tl.fromTo(theSubMenu, 0, {display : 'none'},{display: 'block'}, -0.01);
		tl.staggerFrom(theLinks, 0.2, {y:200, ease:Power4.easeOut}, 0.2);
		$(element).hover(makeItWork, makeItWork)
		function makeItWork() {
		  tl.reversed() ? tl.play(): tl.reverse();
		}
	});

	$("#news").Morphist({
	    animateIn: "tada",
	    animateOut: "bounceOut",
	    speed: 6000,
	    complete: function () {}
	});

	$("#flashinfo").Morphist({
	    animateIn: "slideInUp",
	    animateOut: "tada",
	    speed: 8000,
	    complete: function () {
	    	var im = $('#flashinfo li.slideInUp').attr('image');
	    	$('.oma-menu-image-effect').css({'background-image':'url('+im+')'});
	    }
	});
});