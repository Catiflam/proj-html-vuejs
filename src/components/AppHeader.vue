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
		<div class="container mt-5 d-flex justify-content-around">
			<h3>MASTER <span>Study</span></h3>

			<ul class="link-bar d-flex">
				<li>Courses</li>
				<li>Courses Format</li>
				<li>Add Course</li>
				<li>Pages</li>
				<li>Demos</li>
			</ul>

			<div class="head-icon">
				<i>
					<font-awesome-icon icon="fa-solid fa-house" />
				</i>
				<i>
					<font-awesome-icon icon="fa-solid fa-magnifying-glass" />
				</i>
				<i>
					<font-awesome-icon icon="fa-solid fa-user" />
				</i>
				<i>
					<font-awesome-icon icon="fa-solid fa-star" />
				</i>
			</div>
		</div>
	</header>
</template>

<style lang="scss" scoped>
.head-icon {
	i {
		margin: 6px;
	}
}
</style>
