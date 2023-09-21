<script>
export default {
	data() {
		return {
			links: ["Courses"],
		};
	},
};
</script>

<template>
	<header>
		<div class="container-md fw-bold mb-4 mt-5 d-flex justify-content-around">
			<img src="/public/MasterStudy-1.svg" alt="" />

			<ul class="link-bar d-flex gap-3">
				<li>Courses</li>
				<li>Courses Format</li>
				<li>Add Course</li>
				<li>Pages</li>
				<li>Demos</li>
			</ul>

			<ul class="link-bar d-flex gap-2">
				<li><font-awesome-icon icon="fa-brands fa-linkedin" /></li>
				<li><font-awesome-icon icon="fa-brands fa-instagram" /></li>
				<li><font-awesome-icon icon="fa-brands fa-facebook" /></li>
				<li><font-awesome-icon icon="fa-brands fa-twitter" /></li>
			</ul>
		</div>
	</header>
</template>

<style lang="scss" scoped>
li {
	list-style: none;
	gap: 15px;
}
</style>
