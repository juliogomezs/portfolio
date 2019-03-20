https://owlcarousel2.github.io/OwlCarousel2/

$(".app-carousel").owlCarousel({
				items: 1,
				loop: true,
				autoplay: true,
				smartSpeed: 800,
				margin: 30,
				center: true,
				dots: true,
				responsive: {
					0: {
						items: 1
					},
					480: {
						items: 3
					},
					992: {
						items: 5
					}
				}
			});



/*CSS*/

.app-carousel {
    padding: 0 6%;
}
.app-carousel .center .single-shot {
    opacity: 1;
    transform: scale(1);
}
.app-carousel .single-shot {
    opacity: 0.8;
    transform: scale(0.8);
}

.app-carousel .owl-dots {
    text-align: center;
}
.app-carousel .owl-dot {
    height: 11px;
    width: 11px;
    border: 2px solid #a49fba !important;
    border-radius: 50%;
    margin: 35px 6px;
}
.app-carousel .owl-dot.active {
    background-color: #fb397d;
    border: 0 !important;
}