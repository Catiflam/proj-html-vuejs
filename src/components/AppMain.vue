<script>
export default {};
</script>

<template>
	<!-- PARTE CON TESTI NEL JUMBOTRON INIZIALE -->
	<section class="jumbo">
		<div class="jumbo-text">
			<h1>
				Start Your Human <br />
				<span style="color: #fcb900">Revolution</span>
				Today
			</h1>
			<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. <br />Repellendus sit quod, vel voluptatum eaque doloremque voluptates aperiam !</p>
		</div>
	</section>
	<!-- NAVBAR (ARANCIONE) CENTRALE TRA LE DUE SEZIONI  -->
	<section class="oranje-nav">
		<div class="container-md">
			<nav class="navbar p-4" style="background-color: #fcb900">
				<form class="col-6" role="search">
					<h4 class="mb-4 mt-3"><span style="color: #ffffff">Limited Sale:</span> All courses with 55% off</h4>
					<input class="form-control me-4" type="search" placeholder="Search" aria-label="Search" />
					<button class="btn btn-outline-dark" type="submit">Subscribe</button>
				</form>
				<div class="col">
					<ul>
						<li class="big-num">26</li>
						<li>Days</li>
					</ul>
				</div>
				<div class="col">
					<ul>
						<li class="big-num">01</li>
						<li>Hours</li>
					</ul>
				</div>
				<div class="col">
					<ul>
						<li class="big-num">47</li>
						<li>Minutes</li>
					</ul>
				</div>
				<div class="col">
					<ul>
						<li class="big-num">34</li>
						<li>Seconds</li>
					</ul>
				</div>
			</nav>
		</div>
	</section>

	<!-- SEZIONE DESCRIZIONE PERSONAGGIO -->
	<section class="descript">
		<div class="container-md d-flex justify-content-around">
			<div class="col-4" style="width: 31%">
				<h3 class="mb-5">Hey there my name is Jhon Doe. I'm the founder of Brain Accademy</h3>
				<img src="/public/images/sign-184x108.jpg" class="ms-5" alt="" />
			</div>
			<div class="col-4" style="width: 31%">
				<p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Adipisci ea magnam neque facere maiores laboriosam aut officia ipsam perspiciatis recusandae quidem rerum, commodi ullam excepturi animi beatae sed quisquam enim!</p>
			</div>
		</div>
	</section>
	<!-- SEZIONE CENTRALE CON LE CARD DEI CORSI -->
	<section class="mid-jumbo">
		<div class="container-md text-center">
			<h2 class="p-5">New Courses</h2>
			<div class="row p-0">
				<div class="col-4 mb-3">
					<div class="card ">
							<img src="/public/images/photo-1496307042754-b4aa456c4a2d-370x200.jpeg" class="card-img-top" alt="" />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Electronic</p>
						</div>
						<div class="bar"></div>
						<div class="card-body d-flex">
							<div class="col"><font-awesome-icon icon="fa-solid fa-signal " class="pinted" /> Advance</div>
							<div class="col"><font-awesome-icon icon="fa-solid fa-list-ul" class="pinted" /> 8 Lecture</div>
							<div class="col"><font-awesome-icon icon="fa-regular fa-clock" class="pinted" /> 6 hours</div>
						</div>
					</div>
				</div>
				<div class="col-4">
					<div class="card">
						<img src="/public/images/12345-1-370x200.png" class="card-img-top" alt="..." />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Nvidia</p>
						</div>
						<div class="bar"></div>
						<div class="card-body d-flex">
							<div class="col"><font-awesome-icon icon="fa-solid fa-signal " class="pinted" /> Advance</div>
							<div class="col"><font-awesome-icon icon="fa-solid fa-list-ul" class="pinted" /> 8 Lecture</div>
							<div class="col"><font-awesome-icon icon="fa-regular fa-clock" class="pinted" /> 6 hours</div>
						</div>
					</div>
				</div>
				<div class="col-4">
					<div class="card">
						<img src="/public/images/photo-1491897554428-130a60dd4757-370x200.jpeg" class="card-img-top" alt="..." />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Fascion</p>
						</div>
						<div class="bar"></div>
						<div class="card-body d-flex">
							<div class="col"><font-awesome-icon icon="fa-solid fa-signal " class="pinted" /> Advance</div>
							<div class="col"><font-awesome-icon icon="fa-solid fa-list-ul" class="pinted" /> 8 Lecture</div>
							<div class="col"><font-awesome-icon icon="fa-regular fa-clock" class="pinted" /> 6 hours</div>
						</div>
					</div>
				</div>
				<div class="col-4">
					<div class="card">
						<img src="/public/images/photo-1416339134316-0e91dc9ded92-370x200.jpeg" class="card-img-top" alt="..." />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Comunication</p>
						</div>
						<div class="bar"></div>
						<div class="card-body d-flex">
							<div class="col"><font-awesome-icon icon="fa-solid fa-signal " class="pinted" /> Advance</div>
							<div class="col"><font-awesome-icon icon="fa-solid fa-list-ul" class="pinted" /> 8 Lecture</div>
							<div class="col"><font-awesome-icon icon="fa-regular fa-clock" class="pinted" /> 6 hours</div>
						</div>
					</div>
				</div>
				<div class="col-4">
					<div class="card">
						<img src="/public/images/cathryn-lavery-67852-unsplash-370x200.jpg" class="card-img-top" alt="..." />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Art</p>
						</div>
						<div class="bar"></div>
						<div class="card-body d-flex">
							<div class="col"><font-awesome-icon icon="fa-solid fa-signal " class="pinted" /> Advance</div>
							<div class="col"><font-awesome-icon icon="fa-solid fa-list-ul" class="pinted" /> 8 Lecture</div>
							<div class="col"><font-awesome-icon icon="fa-regular fa-clock" class="pinted" /> 6 hours</div>
						</div>
					</div>
				</div>
				<div class="col-4">
					<div class="card">
						<img src="/public/images/photo-1475452779376-caebfb988090-370x200.jpeg" class="card-img-top" alt="..." />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Bicycling</p>
						</div>
						<div class="bar"></div>
						<div class="card-body d-flex">
							<div class="col"><font-awesome-icon icon="fa-solid fa-signal " class="pinted" /> Advance</div>
							<div class="col"><font-awesome-icon icon="fa-solid fa-list-ul" class="pinted" /> 8 Lecture</div>
							<div class="col"><font-awesome-icon icon="fa-regular fa-clock" class="pinted" /> 6 hours</div>
						</div>
					</div>
				</div>
			</div>
			<button type="button" class="btn btn-warning mt-5 p-2" style="width: 120px">LOAD MORE</button>
		</div>
	</section>
	<!-- SEZIONE DOVE SI TROVA IL LINK DI AMAZON PER ORDINARE IL LIBRO -->
	<section class="alf-jumbo">
		<div class="container-md d-flex justify-content-around align-items-center text-center">
			<div class="col mt-2">
				<h2 class="pinted">Get My Exlusive Investing Book just for $19.50</h2>
				<p style="color: #ffffff">Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus, saepe eveniet cum veniam qui incidunt.</p>
				<div class="amazon">
					<img src="/public/images/amazon.png" alt="" />
				</div>
			</div>
			<div class="col-book">
				<img src="/public/images/book.png" alt="" />
			</div>
		</div>
	</section>
	<!-- SEZIONE IN BASSO CON LE CARD SENZA IMMAGINE E DESCRIZIONE -->
	<section class="mid-end-jumbo">
		<div class="container-md text-center">
			<h2 class="mb-5 p-5">Why my Courses?</h2>
			<div class="row">
				<div class="col-6 mb-3">
					<div class="card card-description">
						<div class="card-body d-flex">
							<div class="col-2"><font-awesome-icon icon="fa-solid fa-briefcase" size="2xl" class="pinted" /></div>
							<div class="col text-start">
								<h5 class="card-title">Entrepreneurship</h5>
								<p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit quidem, tenetur aperiam non dicta est atque numquam consectetur. Laudantium, fugit velit. Beatae reiciendis libero architecto quis obcaecati unde totam repudiandae!</p>
							</div>
						</div>
					</div>
				</div>
				<div class="col-6">
					<div class="card card-description">
						<div class="card-body d-flex">
							<div class="col-2">
								<font-awesome-icon icon="fa-solid fa-rocket" size="2xl" class="pinted" />
							</div>
							<div class="col text-start">
								<h5 class="card-title">Accellerated learning</h5>
								<p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit quidem, tenetur aperiam non dicta est atque numquam consectetur. Laudantium, fugit velit. Beatae reiciendis libero architecto quis obcaecati unde totam repudiandae!</p>
							</div>
						</div>
					</div>
				</div>
				<div class="col-6">
					<div class="card card-description">
						<div class="card-body d-flex">
							<div class="col-2">
								<font-awesome-icon icon="fa-regular fa-thumbs-up" size="2xl" class="pinted" />
							</div>
							<div class="col text-start">
								<h5 class="card-title">Productivity</h5>
								<p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit quidem, tenetur aperiam non dicta est atque numquam consectetur. Laudantium, fugit velit. Beatae reiciendis libero architecto quis obcaecati unde totam repudiandae!</p>
							</div>
						</div>
					</div>
				</div>
				<div class="col-6">
					<div class="card card-description">
						<div class="card-body d-flex">
							<div class="col-2">
								<font-awesome-icon icon="fa-solid fa-gear" size="2xl" class="pinted" />
							</div>
							<div class="col text-start">
								<h5 class="card-title">Life Coaching</h5>
								<p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit quidem, tenetur aperiam non dicta est atque numquam consectetur. Laudantium, fugit velit. Beatae reiciendis libero architecto quis obcaecati unde totam repudiandae!</p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- SEZIONE INBASSO CON SLIDER E COUNTER -->
	<section class="end-jumbo d-flex">
		<div class="container-md d-flex justify-content-around align-items-center">
			<div class="row">
				<div class="col d-flex">
					<div class="col-2">
						<font-awesome-icon icon="fa-solid fa-user-group" size="2xl" class="white" />
					</div>
					<div class="col">
						<ul>
							<li class="big-num">3195</li>
							<p>Online Learner</p>
						</ul>
					</div>
				</div>
				<div class="col d-flex">
					<div class="col-2">
						<font-awesome-icon icon="fa-solid fa-film" size="2xl" class="white" />
					</div>
					<div class="col">
						<ul>
							<li class="big-num">23</li>
							<p>Video Courses</p>
						</ul>
					</div>
				</div>
				<div class="col d-flex">
					<div class="col-2">
						<font-awesome-icon icon="fa-regular fa-image" size="2xl" class="white" />
					</div>
					<div class="col">
						<ul>
							<li class="big-num">437</li>
							<p>Sliders&Immage</p>
						</ul>
					</div>
				</div>
				<div class="col d-flex">
					<div class="col-2">
						<font-awesome-icon icon="fa-regular fa-thumbs-up" size="2xl" class="white" />
					</div>
					<div class="col">
						<ul>
							<li class="big-num">1440</li>
							<p>Exellent Reviews</p>
						</ul>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- SEZIONE COSA DICONO GLI STUDENTI -->
	<section class="students-say">
		<div class="container">
			<div class="d-flex flex-column align-items-center">
				<h3 class="p-5">What Students Say</h3>
				<div class="circle-img">
					<font-awesome-icon icon="fa-solid fa-arrow-left" size="2xl" class="arrow"/>
					<img src="/public/images/1-100x100.jpg" alt="" />
					<img src="/public/images/2-100x100.jpg" class="big-img" alt="" />
					<img src="/public/images/4-100x100.jpg" alt="" />
					<font-awesome-icon icon="fa-solid fa-arrow-right" size="2xl" class="arrow"/>
				</div>
				<h5 class="p-3">Paints of the Future</h5>

				<div class="d-flex stars">
					<font-awesome-icon icon="fa-solid fa-star" size="xs" class="pinted" />
					<font-awesome-icon icon="fa-solid fa-star" size="xs" class="pinted" />
					<font-awesome-icon icon="fa-solid fa-star" size="xs" class="pinted" />
					<font-awesome-icon icon="fa-solid fa-star" size="xs" class="pinted" />
					<font-awesome-icon icon="fa-solid fa-star" size="xs" class="pinted" />
				</div>

				<p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Adipisci ea magnam neque facere maiores laboriosam aut officia ipsam perspiciatis recusandae quidem rerum, commodi ullam excepturi animi beatae sed quisquam enim!</p>
			</div>
		</div>
	</section>
	<!-- SEZIONE FINALE -->
	<section class="footer" style="background-color: #fcb900">
		<div class="container p-5">
			<div class="row">
				<div class="col">
					<h4>About us</h4>
					<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ex, dignissimos iure. Id aperiam tempore impedit numquam ipsum voluptate ex error quis facere officia.</p>
					<font-awesome-icon icon="fa-brands fa-facebook" />
					<font-awesome-icon icon="fa-brands fa-twitter" />
					<font-awesome-icon icon="fa-brands fa-instagram" />
				</div>
				<div class="col">
					<h4>Contacts</h4>
					<address>Usa california 20, First Avenue, California</address>
					<address>
						Tel:+12578458
						<p>Fax:+21115455</p>
					</address>
					<a href="">info@masterstydy.com</a>
				</div>
				<div class="col">
					<h4>Pages</h4>
					<ul>
						<li>Blog</li>
						<li>Home</li>
						<li>Shortcodes</li>
					</ul>
				</div>
				<div class="col">
					<div style="color: #fcb900">vuoto</div>
					<ul>
						<li>Curses</li>
						<li>Membership A.</li>
						<li>Typography</li>
					</ul>
				</div>
				<div class="col-1 w-5">
					<h4>Blog</h4>
					<div class="col">
						<div>
							<img src="/public/images/photo-1517520287167-4bbf64a00d66-50x50.jpeg" alt="" />
						</div>

						<div class="mt-2">
							<img src="/public/images/photo-1490376840453-5f616fbebe5b-50x50.jpeg" alt="" />
						</div>
					</div>
				</div>
				<div class="col figcap">
					<div style="color: #fcb900">vuoto</div>
					<p>Our main target is to 'Developing Yourself as a Leader' 
						<address>- August 9 2018</address>
					</p>
					<p>Those Other College Expenses You Aren't Tinking About
						<address>- June 3 2015</address>
					</p>
				</div>
			</div>
		</div>
	</section>
</template>

<style lang="scss" scoped>
@use "./style/style.scss" as *;
</style>
