<template>
	<div class="single-post-page">
		<section class="post">
			<h1 class="post-title">
				Title
			</h1>

			<div class="post-details">
				<div class="post-detail">
					Last updated on XXXXX
				</div>

				<div class="post-detail">
					Written by name....
				</div>

				<p class="post-content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora corporis, aliquam obcaecati at dolorem nemo libero necessitatibus, vitae odio velit doloremque. Consectetur nulla veniam voluptas sint sit beatae molestiae exercitationem.</p>
			</div>
		</section>

		<section class="post-feedback">
			<p>Please send feedback to <a href="mailto:test@example.com">test@example.com</a>.</p>
		</section>
	</div>
</template>

<script>
export default {

}
</script>

<style scoped>
.single-post-page {
  padding: 30px;
  text-align: center;
  box-sizing: border-box;
}

.post {
  width: 100%;
}

@media (min-width: 768px) {
  .post {
    width: 600px;
    margin: auto;
  }
}

.post-title {
  margin: 0;
}

.post-details {
  padding: 10px;
  box-sizing: border-box;
  border-bottom: 3px solid #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

@media (min-width: 768px) {
  .post-details {
    flex-direction: row;
  }
}

.post-detail {
  color: rgb(88, 88, 88);
  margin: 0 10px;
}

.post-feedback a {
  color: red;
  text-decoration: none;
}

.post-feedback a:hover,
.post-feedback a:active {
  color: salmon;
}
</style>