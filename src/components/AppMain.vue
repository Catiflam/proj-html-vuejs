<script>
export default {};
</script>

<template>
	<!-- PARTE CON TESTI NEL JUMBOTRON INIZIALE -->
	<section class="jumbo">
		<div class="jumbo-text">
			<h1>
				Start Your Human <br />
				<span class="text-yellow">Revolution</span>
				Today
			</h1>
			<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. <br />Repellendus sit quod, vel voluptatum eaque doloremque voluptates aperiam !</p>
		</div>
	</section>
	<!-- NAVBAR (ARANCIONE) CENTRALE TRA LE DUE SEZIONI  -->
	<section>
		<div class="offer container">
			<nav class="navbar p-4" style="background-color: #fcb900">
				<h3>Limited Sale: <span>All courses with 55% off</span></h3>
				<div class="container-fluid">
					<form class="d-flex w-25" role="search">
						<input class="form-control me-4" type="search" placeholder="Search" aria-label="Search" />
						<button class="btn btn-outline-success" type="submit">Search</button>
						<div><span>26</span> <span>days</span></div>
						<div><span>26</span> <span>hours</span></div>
						<div><span>26</span> <span>minutes</span></div>
						<div><span>26</span> <span>seconds</span></div>
					</form>
				</div>
			</nav>
		</div>
	</section>

	<!-- SEZIONE DESCRIZIONE PERSONAGGIO -->
	<section>
		<div class="container d-flex justify-content-around">
			<div class="col-4">
				<h3>Hey there my name is Jhon Doe. I'm the founder of Brain Accademy</h3>
				<img src="/public/images/sign-184x108.jpg" alt="" />
			</div>
			<div class="col-4">
				<p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Adipisci ea magnam neque facere maiores laboriosam aut officia ipsam perspiciatis recusandae quidem rerum, commodi ullam excepturi animi beatae sed quisquam enim!</p>
			</div>
		</div>
	</section>
	<!-- SEZIONE CENTRALE CON LE CARD DEI CORSI -->
	<section class="mid-jumbo">
		<div class="container text-center">
			<h2>New Courses</h2>
			<div class="row">
				<div class="col-4">
					<div class="card">
						<img src="/public/images/photo-1496307042754-b4aa456c4a2d-370x200.jpeg" class="card-img-top" alt="..." />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Electronic</p>
						</div>
						<div class="card-body">
							<font-awesome-icon icon="fa-solid fa-signal" />
							<font-awesome-icon icon="fa-solid fa-list-ul" />
							<font-awesome-icon icon="fa-regular fa-clock" />
						</div>
					</div>
				</div>
				<div class="col-4">
					<div class="card">
						<img src="/public/images/12345-1-370x200.png" class="card-img-top" alt="..." />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Electronic</p>
						</div>
						<div class="card-body">
							<font-awesome-icon icon="fa-solid fa-signal" />
							<font-awesome-icon icon="fa-solid fa-list-ul" />
							<font-awesome-icon icon="fa-regular fa-clock" />
						</div>
					</div>
				</div>
				<div class="col-4">
					<div class="card">
						<img src="/public/images/photo-1491897554428-130a60dd4757-370x200.jpeg" class="card-img-top" alt="..." />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Electronic</p>
						</div>
						<div class="card-body">
							<font-awesome-icon icon="fa-solid fa-signal" />
							<font-awesome-icon icon="fa-solid fa-list-ul" />
							<font-awesome-icon icon="fa-regular fa-clock" />
						</div>
					</div>
				</div>
				<div class="col-4">
					<div class="card">
						<img src="/public/images/photo-1416339134316-0e91dc9ded92-370x200.jpeg" class="card-img-top" alt="..." />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Electronic</p>
						</div>
						<div class="card-body">
							<font-awesome-icon icon="fa-solid fa-signal" />
							<font-awesome-icon icon="fa-solid fa-list-ul" />
							<font-awesome-icon icon="fa-regular fa-clock" />
						</div>
					</div>
				</div>
				<div class="col-4">
					<div class="card">
						<img src="/public/images/cathryn-lavery-67852-unsplash-370x200.jpg" class="card-img-top" alt="..." />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Electronic</p>
						</div>
						<div class="card-body">
							<font-awesome-icon icon="fa-solid fa-signal" />
							<font-awesome-icon icon="fa-solid fa-list-ul" />
							<font-awesome-icon icon="fa-regular fa-clock" />
						</div>
					</div>
				</div>
				<div class="col-4">
					<div class="card">
						<img src="/public/images/photo-1475452779376-caebfb988090-370x200.jpeg" class="card-img-top" alt="..." />
						<div class="card-body">
							<h5 class="card-title">How to be a DJ? Make Electronics Music</h5>
							<p class="card-text">Electronic</p>
						</div>
						<div class="card-body">
							<font-awesome-icon icon="fa-solid fa-signal" />
							<font-awesome-icon icon="fa-solid fa-list-ul" />
							<font-awesome-icon icon="fa-regular fa-clock" />
						</div>
					</div>
				</div>
			</div>
			<button type="button" class="btn btn-warning mt-5">Warning</button>
		</div>
	</section>
	<!-- SEZIONE DOVE SI TROVA IL LINK DI AMAZON PER ORDINARE IL LIBRO -->
	<section class="alf-jumbo">
		<div class="container d-flex justify-content-around align-items-center">
			<div class="col-2 mt-2">
				<h2>get My Exlusive Investing Book just for $19.50</h2>
				<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus, saepe eveniet cum veniam qui incidunt.</p>
				<img src="/public/images/amazon.png" alt="" />
			</div>
			<div class="col-2">
				<img src="/public/images/book.png" alt="" />
			</div>
		</div>
	</section>
	<!-- SEZIONE IN BASSO CON LE CARD SENZA IMMAGINE E DESCRIZIONE -->
	<section class="mid-jumbo">
		<div class="container text-center">
			<h2>Why my Courses?</h2>
			<div class="row">
				<div class="col-6">
					<div class="card">
						<div class="card-body">
							<h5 class="card-title">Entrepreneurship</h5>
							<p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit quidem, tenetur aperiam non dicta est atque numquam consectetur. Laudantium, fugit velit. Beatae reiciendis libero architecto quis obcaecati unde totam repudiandae!</p>
						</div>
						<div class="card-body">
							<font-awesome-icon icon="fa-solid fa-signal" />
						</div>
					</div>
				</div>
				<div class="col-6">
					<div class="card">
						<div class="card-body">
							<h5 class="card-title">Accellerated learning</h5>
							<p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit quidem, tenetur aperiam non dicta est atque numquam consectetur. Laudantium, fugit velit. Beatae reiciendis libero architecto quis obcaecati unde totam repudiandae!</p>
						</div>
						<div class="card-body">
							<font-awesome-icon icon="fa-solid fa-signal" />
						</div>
					</div>
				</div>
				<div class="col-6">
					<div class="card">
						<div class="card-body">
							<h5 class="card-title">Productivity</h5>
							<p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit quidem, tenetur aperiam non dicta est atque numquam consectetur. Laudantium, fugit velit. Beatae reiciendis libero architecto quis obcaecati unde totam repudiandae!</p>
						</div>
						<div class="card-body">
							<font-awesome-icon icon="fa-solid fa-signal" />
						</div>
					</div>
				</div>
				<div class="col-6">
					<div class="card">
						<div class="card-body">
							<h5 class="card-title">Life Coaching</h5>
							<p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugit quidem, tenetur aperiam non dicta est atque numquam consectetur. Laudantium, fugit velit. Beatae reiciendis libero architecto quis obcaecati unde totam repudiandae!</p>
						</div>
						<div class="card-body">
							<font-awesome-icon icon="fa-solid fa-signal" />
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- SEZIONE INBASSO CON SLIDER E COUNTER -->
	<section class="end-jumbo">
		<div class="container d-flex justify-content-around align-items-center">
			<div>
				<font-awesome-icon icon="fa-solid fa-user-group" size="2xl" />
				<font-awesome-icon icon="fa-solid fa-film" size="2xl" />
				<font-awesome-icon icon="fa-regular fa-image" size="2xl" />
				<font-awesome-icon icon="fa-regular fa-thumbs-up" size="2xl" />
			</div>
		</div>
	</section>
	<!-- SEZIONE COSA DICONO GLI STUDENTI -->
	<section class="students-say">
		<div class="container">
			<div class="d-flex flex-column align-items-center">
				<h3>What Students Say</h3>
				<div>
					<img src="/public/images/1-100x100.jpg" alt="" />
					<img src="/public/images/2-100x100.jpg" alt="" />
					<img src="/public/images/4-100x100.jpg" alt="" />
				</div>
				<h5>Paints of the Future</h5>

				<p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Adipisci ea magnam neque facere maiores laboriosam aut officia ipsam perspiciatis recusandae quidem rerum, commodi ullam excepturi animi beatae sed quisquam enim!</p>
			</div>
		</div>
	</section>
	<!-- SEZIONE FINALE -->
	<section class="footer" style="background-color: #fcb900">
		<div class="container">
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
					<div></div>
					<ul>
						<li>Curses</li>
						<li>Membership A.</li>
						<li>Typography</li>
					</ul>
				</div>
				<div class="col">
					<h4>Blog</h4>
					<img src="/public/images/photo-1517520287167-4bbf64a00d66-50x50.jpeg" alt="" />
					<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, repellendus officiis nulla molestiae, doloremque</p>

					<img src="/public/images/photo-1490376840453-5f616fbebe5b-50x50.jpeg" alt="" />
					<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, repellendus officiis nulla molestiae, doloremque</p>
				</div>
			</div>
		</div>
	</section>
</template>

<style lang="scss" scoped>
@use "./style/style.scss" as *;
</style>
