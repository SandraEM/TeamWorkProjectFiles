<head>

<script>
  document.addEventListener( 'DOMContentLoaded', function () {
    new Splide( '#image-carousel' ).mount();
  } );
</script>

</head>

<body>

<section id="image-carousel" class="splide" aria-label="Biscuit Images">
  <div class="splide__track">
		<ul class="splide__list">
			<li class="splide__slide">
				<img src="ImagePenguinplate1.jpg" alt="">
			</li>
			<li class="splide__slide">
				<img src="ImageViennese.jpg" alt="">
			</li>
			<li class="splide__slide">
				<img src="ImageCustardCream.jpg" alt="">
			</li>
		</ul>
  </div>

.splide__slide img {
  width: 100%;
  height: auto;
}

</section>


</body>

