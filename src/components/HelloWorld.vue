<template>
	<nav>
		<div class="top-nav flex-end-position">
			<div class="burger-top-menu">
				<ion-icon name="menu-sharp"></ion-icon>
			</div>
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
			<div class="flex-center-position skills-title">
				<h1 id="skills">Umiejętności</h1>
			</div>
			<div class="skills flex-center-position">
				<div class="flex-center-position">
					<div class="html">
						<div class="html-card skills-icon">
							<ion-icon name="logo-html5"></ion-icon>
						</div>
					</div>
					<div class="css">
						<div class="css-card skills-icon">
							<ion-icon name="logo-css3"></ion-icon>
						</div>
					</div>
					<div class="javascript">
						<div class="javascript-card skills-icon">
							<ion-icon name="logo-javascript"></ion-icon>
						</div>
					</div>
					<div class="github">
						<div class="github-card skills-icon">
							<ion-icon name="logo-github"></ion-icon>
						</div>
					</div>
					<div class="scss skills-icon">
						<div class="scss-card"><ion-icon name="logo-sass"></ion-icon></div>
					</div>
					<div class="vue-card skills-icon">
						<ion-icon name="logo-vue"></ion-icon>
					</div>
				</div>
			</div>
		</section>
	</main>
</template>
<style scoped lang="scss">
@import '../scss/style.scss';
</style>
