<script setup>
</script>

<template>
	<header class="header">
		<div class="container">

			<nav class="header__nav">
				<div class="logo">
					<a href="#" class="logo__link">Panto</a>
				</div>

				<ul class="menu menu_header">
					<li class="menu__item menu__item_drop_down">
						<a href="#" class="menu__link">Furniture</a>
						<i class="bi-chevron-down"></i>

						<ul class="menu menu__submenu">
							<li class="menu__subitem">Chair</li>
							<li class="menu__subitem">Bends</li>
							<li class="menu__subitem">Sofa</li>
							<li class="menu__subitem">Lamp</li>
						</ul>
					</li>
					<li class="menu__item"><a href="#" class="menu__link">Shop</a></li>
					<li class="menu__item"><a href="#" class="menu__link">About Us</a></li>
					<li class="menu__item"><a href="#" class="menu__link">Contacts</a></li>
				</ul>

				<button class="header__burger">
					<i class="bi-list"></i>
				</button>

				<div class="basket">
					<i class="basket__icon bi-handbag-fill"></i>
					<span class="basket__counter">0</span>
				</div>
			</nav>

			<h1 class="header__slogan">Make your interior more minimalistic & modern</h1>

			<h2 class="header__subtitle">Turn your room with panto into a lot more minimalist
				and modern with ease and speed</h2>

			<div class="search header__search">
				<input type="text" placeholder="Search furniture" class="search__input">

				<button class="search__button">
					<i class="bi-search"></i>
				</button>
			</div>

		</div>
	</header>

	<main>
		<section class="section section_about">
			<div class="container">

				<div class="section__row">
					<div class="section__column">
						<h2 class="section__title">Why Choosing Us</h2>
					</div>

					<div class="section__grid">
						<article class="section__column">
							<h3 class="section__subtitle">Luxury facilities</h3>

							<p class="section__paragraph">The advantage of hiring a workspace with us is that givees you
								comfortable service and all-around facilities.</p>

							<a href="#" class="section__link">
								<span class="section__text">More info</span>
								<i class="bi-arrow-right"></i>
							</a>
						</article>

						<article class="section__column">
							<h3 class="section__subtitle">Affordable Price</h3>

							<p class="section__paragraph">You can get a workspace of the highst quality at an affordable price and
								still enjoy the facilities that are oly here.</p>

							<a href="#" class="section__link">
								<span class="section__text">More info</span>
								<i class="bi-arrow-right"></i>
							</a>
						</article>

						<article class="section__column">
							<h3 class="section__subtitle">Many Choices</h3>

							<p class="section__paragraph">We provide many unique work space choices so that you can choose the
								workspace to your liking.</p>

							<a href="#" class="section__link">
								<span class="section__text">More info</span>
								<i class="bi-arrow-right"></i>
							</a>
						</article>
					</div>
				</div>

			</div>
		</section>

		<section class="section section_carousel">
			<div class="container">
				<h2 class="section__title">Best Selling Product</h2>
				
				<article class="carousel">
					<div class="carousel__panel">
						<button class="carousel__button carousel__button_active">Chair</button>
						<button class="carousel__button">Beds</button>
						<button class="carousel__button">Sofa</button>
						<button class="carousel__button">Lamp</button>
					</div>

					<div class="carousel__inner">
						<button class="carousel__control carousel__control_prev">
							<i class="bi-arrow-left"></i>
						</button>

						<button class="carousel__control carousel__control_next">
							<i class="bi-arrow-right"></i>
						</button>

						<article class="product">
							<figure class="product__header">
								<img src="./assets/images/chair1.png" alt="chair" class="product__image">
							</figure>

							<figcaption class="product__caption">
								<h4 class="product__category">Chair</h4>
								<h3 class="product__name">Sakarias Armchair</h3>

								<div class="rating product__rating">
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
								</div>

								<div class="product__bottom">
									<div class="product__price">
										<sup class="product__sup">$</sup>392
									</div>

									<button class="product__button">
										<i class="bi-plus-lg"></i>
									</button>
								</div>
							</figcaption>
						</article>
						
						<article class="product">
							<figure class="product__header">
								<img src="./assets/images/chair2.png" alt="chair" class="product__image">
							</figure>

							<figcaption class="product__caption">
								<h4 class="product__category">Chair</h4>
								<h3 class="product__name">Baltsar Chair</h3>

								<div class="rating product__rating">
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
								</div>

								<div class="product__bottom">
									<div class="product__price">
										<sup class="product__sup">$</sup>299
									</div>

									<button class="product__button">
										<i class="bi-plus-lg"></i>
									</button>
								</div>
							</figcaption>
						</article>
						
						<article class="product">
							<figure class="product__header">
								<img src="./assets/images/chair3.png" alt="chair" class="product__image">
							</figure>

							<figcaption class="product__caption">
								<h4 class="product__category">Chair</h4>
								<h3 class="product__name">Anjay Chair</h3>

								<div class="rating product__rating">
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
								</div>

								<div class="product__bottom">
									<div class="product__price">
										<sup class="product__sup">$</sup>519
									</div>

									<button class="product__button">
										<i class="bi-plus-lg"></i>
									</button>
								</div>
							</figcaption>
						</article>
						
						<article class="product">
							<figure class="product__header">
								<img src="./assets/images/chair4.png" alt="chair" class="product__image">
							</figure>

							<figcaption class="product__caption">
								<h4 class="product__category">Chair</h4>
								<h3 class="product__name">Nyantuy Chair</h3>

								<div class="rating product__rating">
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
									<i class="rating__icon bi-star-fill"></i>
								</div>

								<div class="product__bottom">
									<div class="product__price">
										<sup class="product__sup">$</sup>921
									</div>

									<button class="product__button">
										<i class="bi-plus-lg"></i>
									</button>
								</div>
							</figcaption>
						</article>
					</div>
				</article>

			</div>
		</section>
	</main>

	<footer class="section section_footer" id="footer">
		<div class="container">
			<div class="section__row">
				<div class="section__column">
					<div class="logo logo_dark">
						<a href="#" class="logo__link">Panto</a>
					</div>

					<p class="section__paragraph">The advantage of hiring a workspace with us is that givees you comfortable
						service and all-around facilities.</p>
				</div>

				<div class="section__grid">
					<ul class="menu menu_footer">
						<li class="menu__item">
							<h3 class="menu__title">Services</h3>
						</li>
						<li class="menu__item"><a href="#" class="menu__link">Email Marketing</a></li>
						<li class="menu__item"><a href="#" class="menu__link">Campaigns</a></li>
						<li class="menu__item"><a href="#" class="menu__link">Branding</a></li>
					</ul>

					<ul class="menu menu_footer">
						<li class="menu__item">
							<h3 class="menu__title">Furniture</h3>
						</li>
						<li class="menu__item"><a href="#" class="menu__link">Beds</a></li>
						<li class="menu__item"><a href="#" class="menu__link">Chair</a></li>
						<li class="menu__item"><a href="#" class="menu__link">All</a></li>
					</ul>

					<ul class="menu menu_footer">
						<li class="menu__item">
							<h3 class="menu__title">Follow Us</h3>
						</li>
						<li class="menu__item">
							<a href="#" class="menu__link">
								<i class="bi-facebook"></i>
								<span class="menu__text">Facebook</span>
							</a>
						</li>
						<li class="menu__item">
							<a href="#" class="menu__link">
								<i class="bi-twitter"></i>
								<span class="menu__text">Twitter</span>
							</a>
						</li>
						<li class="menu__item">
							<a href="#" class="menu__link">
								<i class="bi-instagram"></i>
								<span class="menu__text">Instagram</span>
							</a>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</footer>

</template>

<style scoped>

</style>
