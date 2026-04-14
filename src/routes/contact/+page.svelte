<script>
	import ContactForm from '$lib/components/ContactForm.svelte'
	import PageTitle from '$lib/components/PageTitle.svelte'
</script>

<svelte:head>
	<title>Contact | Acme Corporation</title>
	<meta name="description" content="Lorem ipsum dolor sit amet consectetur adipisicing elit. Sed officiis provident perspiciatis rem impedit maxime?">
</svelte:head>

<PageTitle title="Contact"></PageTitle>

<section>
	<div class="outer">
		<div class="inner">
			<h2>Send a Message</h2>
			<ContactForm></ContactForm>
		</div>
	</div>
</section>