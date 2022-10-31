<template>
	<nav>
		<div class="top-nav flex flex-end">
			<div class="burger-top-menu">
				<ion-icon name="menu-sharp"></ion-icon>
			</div>
			<div><a class="top-nav-element" href="#home">Strona główna</a></div>
			<div><a class="top-nav-element" href="#aboutme">O mnie</a></div>
			<div><a class="top-nav-element" href="#goals">Osiągnięcia</a></div>
			<div><a class="top-nav-element" href="#skills">Umiejętności</a></div>
			<div><a class="top-nav-element" href="#project">Projekty</a></div>
			<div><a class="top-nav-element" href="#contact">Kontakt</a></div>
		</div>
	</nav>
	<header id="home">
		<div class="header-background flex center text-center item-center">
			<div class="shadow-header-background"></div>
			<div class="welcome-text text-center">
				<h1 class="text-center">Witaj, chcesz nieco więcej dowiedzieć się o mnie?</h1>
				<a href="#aboutme" class="welcome-button">Przejdź dalej</a>
			</div>
		</div>
	</header>
	<main>
		<section id="aboutme" class="about-me flex item-center center column">
			<h2 class="text-center">O <span class="color-header-text">mnie</span></h2>
			<div class="flex flex-space-around mobile">
				<div class="section-about-me flex center">
					<div class="flex center item-center text-about-me test1">
						<p>
							Jestem na 5 semestrze studiowania w Wyższej szkole informatyki i zarządzania w Bielsko-Biała.
							Hobbystycznie zajmuje się projektowaniem stron internetowym. Głównie pracuje z technologami Front-End.
							Głównie interesuje się najnowszymi ciekawostkami z świata IT. Lubię dobre jedzenie i podróżowanie
						</p>
					</div>
				</div>
				<div class="flex center test2" data-aos="fade-left">
					<img src="../picture/my-photo.jpg" alt="foto" class="foto-about-me" />
				</div>
			</div>
		</section>
		<section>
			<div class="skills">
				<div>
					<h1 id="skills" class="text-center">Umiejętności</h1>
				</div>
				<div class="flex center mobile-column">
					<div>
						<div class="html-card skills-icon">
							<ion-icon name="logo-html5"></ion-icon>
							<div class="skill-level">
								<div class="html-skill-level"></div>
							</div>
						</div>
					</div>
					<div>
						<div class="skills-icon">
							<ion-icon name="logo-css3"></ion-icon>
							<div class="skill-level">
								<div class="css-skill-level"></div>
							</div>
						</div>
					</div>
					<div>
						<div class="skills-icon">
							<ion-icon name="logo-javascript"></ion-icon>
							<div class="skill-level">
								<div class="js-skill-level"></div>
							</div>
						</div>
					</div>
				</div>
				<div class="flex center mobile-column">
					<div>
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
				<h1 class="text-center">Osiągnięcia</h1>
			</div>
		</section>
		<section>
			<div class="contact">
				<h1 id="contact" class="text-center">kontakt</h1>
				<div class="flex column item-center">
					<p class="text-center">Chcesz nawiązać współprace? Wyślij wiadomość</p>
					<textarea placeholder="Twoja wiadomość" class="contact-textarea"></textarea>
					<button class="contact-btn">Wyślij wiadomość</button>
				</div>
			</div>
		</section>
	</main>
	<footer class="footer">
		<div class="flex flex-space-around center-content mobile">
			<div>
				<div class="text-center">
					<h2 class="contact-space-icon">Kontakt</h2>
				</div>
				<div class="mobile-footer flex row space-p">
					<ion-icon name="mail-outline"></ion-icon>
					<p class="mobile-footer contact-space-icon">krzysztof.kleka@poczta.onet.pl</p>
				</div>
				<div class="mobile-footer flex row space-p">
					<ion-icon name="logo-linkedin"></ion-icon>
					<p class="contact-space-icon">Krzysztof Klęka</p>
				</div>
				<div class="mobile-footer flex row space-p">
					<ion-icon name="logo-github"></ion-icon>
					<p class="contact-space-icon">Kry765</p>
				</div>
				<div class="mobile-footer flex row space-p">
					<ion-icon name="logo-discord"></ion-icon>
					<p class="contact-space-icon">Kry765#5652</p>
				</div>
			</div>
			<div class="footer-center-position">
				<div class="text-center">
					<h2>Adres</h2>
				</div>
				<div class="mobile-footer flex row space-p">
					<ion-icon name="person-circle-outline"></ion-icon>
					<p class="contact-space-icon">Krzysztof Klęka</p>
				</div>
				<div class="mobile-footer flex row space-p">
					<ion-icon name="location-outline"></ion-icon>
					<p class="contact-space-icon">Żywiec</p>
				</div>
				<div class="mobile-footer flex row space-p">
					<ion-icon name="phone-portrait-outline"></ion-icon>
					<p class="contact-space-icon">573-226-219</p>
				</div>
			</div>
			<div>
				<div class="text-center">
					<h2>Menu</h2>
				</div>
				<div class="bottom-menu"><a href="#home">Strona główna</a></div>
				<div class="bottom-menu"><a href="#aboutme">O mnie</a></div>
				<div class="bottom-menu"><a href="#goals">Osiągnięcia</a></div>
				<div class="bottom-menu"><a href="#skills">Umiejętności</a></div>
				<div class="bottom-menu"><a href="#contact">Kontakt</a></div>
			</div>
		</div>
		<div class="copyright">
			<p class="text-center">2022 &copy; Kry765</p>
		</div>
	</footer>
</template>
<style scoped lang="scss">
@import '../scss/style.scss';
@import '../scss/mobile.scss';
</style>
