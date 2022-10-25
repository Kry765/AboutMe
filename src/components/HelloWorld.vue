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
			<div class="skills">
				<div class="flex-center-position skills-title">
					<h1 id="skills">Umiejętności</h1>
				</div>
				<div class="flex-center-position">
					<div class="html">
						<div class="html-card skills-icon">
							<ion-icon name="logo-html5"></ion-icon>
							<div class="skill-level">
								<div class="html-skill-level"></div>
							</div>
						</div>
					</div>
					<div class="css">
						<div class="skills-icon">
							<ion-icon name="logo-css3"></ion-icon>
							<div class="skill-level">
								<div class="css-skill-level"></div>
							</div>
						</div>
					</div>
					<div class="javascript">
						<div class="skills-icon">
							<ion-icon name="logo-javascript"></ion-icon>
							<div class="skill-level">
								<div class="js-skill-level"></div>
							</div>
						</div>
					</div>
				</div>
				<div class="flex-center-position">
					<div class="github">
						<div class="skills-icon">
							<ion-icon name="logo-github"></ion-icon>
							<div class="skill-level">
								<div class="github-skill-level"></div>
							</div>
						</div>
					</div>
					<div class="skills-icon">
						<div class="scss-card">
							<ion-icon name="logo-sass"></ion-icon>
							<div class="skill-level">
								<div class="scss-skill-card"></div>
							</div>
						</div>
					</div>

					<div class="skills-icon">
						<ion-icon name="logo-vue"></ion-icon>
						<div class="skill-level">
							<div class="vue-skill-level"></div>
						</div>
					</div>
				</div>
			</div>
		</section>
		<section>
			<div class="goals">
				<div class="shadow-goals"></div>
				<h1>Osiągnięcia</h1>
			</div>
		</section>
		<section>
			<div class="contact">
				<div class="email">
					<p>Chcesz nawiązać współprace? Wyślij wiadomość</p>
					<textarea placeholder="Twoja wiadomość"></textarea>
					<button>Wyślij wiadomość</button>
				</div>
				<div class="flex-end-position">
					<div>
						<ion-icon name="logo-linkedin"></ion-icon>
						<p>LinkedIn</p>
					</div>
					<div>
						<ion-icon name="logo-github"></ion-icon>
						<p>github</p>
					</div>
					<div>
						<ion-icon name="logo-facebook"></ion-icon>
						<p>facebook</p>
					</div>
					<div>
						<ion-icon name="logo-facebook"></ion-icon>
						<p>E-mail</p>
					</div>
				</div>
			</div>
		</section>
	</main>
	<footer>
		<div class="footer">
			<p>2022&copy; Kry765</p>
		</div>
	</footer>
</template>
<style scoped lang="scss">
@import '../scss/style.scss';
</style>
