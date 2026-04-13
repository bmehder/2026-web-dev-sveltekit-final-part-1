<script>
	import PageTitle from '$lib/components/PageTitle.svelte'
</script>

<PageTitle title="Welcome to Acme Corporation"></PageTitle>

<section>
	<div class="outer">
		<div class="inner">
			<h2>Section 1</h2>
			<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Esse possimus vel id adipisci officiis assumenda? Adipisci ab maiores dicta consectetur praesentium, laudantium eum nobis in at, assumenda dolore placeat provident enim! Eaque sint repellendus culpa quasi labore, odit exercitationem ipsa modi quod tenetur molestias doloribus sit consequuntur quaerat eius dolor! Voluptatum, hic!</p>
		</div>
	</div>
</section>

<section class="section-2">
	<div class="outer">
		<div class="inner">
			<h2 class="sr-only">Section 2</h2>
			<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Esse possimus vel id adipisci officiis assumenda? Adipisci ab maiores dicta consectetur praesentium, laudantium eum nobis in at, assumenda dolore placeat provident enim! Eaque sint repellendus culpa quasi labore, odit exercitationem ipsa modi quod tenetur molestias doloribus sit consequuntur quaerat eius dolor! Voluptatum, hic!</p>
		</div>
	</div>
</section>

<section>
	<div class="outer">
		<div class="inner">
			<h2>Section 3</h2>
			<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Esse possimus vel id adipisci officiis assumenda? Adipisci ab maiores dicta consectetur praesentium, laudantium eum nobis in at, assumenda dolore placeat provident enim! Eaque sint repellendus culpa quasi labore, odit exercitationem ipsa modi quod tenetur molestias doloribus sit consequuntur quaerat eius dolor! Voluptatum, hic!</p>
		</div>
	</div>
</section>

<aside class="resources">
	<div class="outer">
		<div class="inner">
			<h3>Resources:</h3>
			<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
		</div>
	</div>
</aside>


<style>
	.section-2 .outer {
		background-color: dodgerblue;
		color: white;
	}

	.resources .inner {
		border-top: 1px solid;
	}	
</style>