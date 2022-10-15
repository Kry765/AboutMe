<template>
	<nav>
		<div class="top-nav flex-end-position">
			<div><a class="top-nav-element" href="#home">Strona główna</a></div>
			<div><a class="top-nav-element" href="#aboutme">O mnie</a></div>
			<div><a class="top-nav-element" href="#goals">Osiągnięcia</a></div>
			<div><a class="top-nav-element" href="#skills">Umiejętności</a></div>
			<div><a class="top-nav-element" href="#contact">Kontakt</a></div>
		</div>
	</nav>
	<header id="home">
		<div class="header-background flex-center-position">
			<div class="shadow-header-background"></div>
			<div class="welcome-text">
				<h1>Witaj, chcesz nieco więcej dowiedzieć się o mnie?</h1>
				<br />
				<a href="#aboutme" class="welcome-button">Przejdź dalej</a>
			</div>
		</div>
	</header>
	<main>
		<section>
			<div class="about-me" id="aboutme"></div>
		</section>
	</main>
</template>
<style scoped lang="scss">
@import '../scss/style.scss';
</style>
