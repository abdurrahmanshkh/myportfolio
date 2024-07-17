<script>
	import '../app.pcss';
	import Header from './header.svelte';
	import Footer from './footer.svelte';
</script>

<svelte:head>
	<title>Abdur Rehman Shaikh | Portfolio</title>
	<meta name="description" content="The portfolio of Abdur Rehman Shaikh, showcasing projects and skills in web development and software engineering.">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta name="author" content="Abdur Rehman Shaikh">
	<meta name="keywords" content="Abdur Rehman Shaikh, portfolio, web development, software engineering, Svelte, SvelteKit">
	<!-- Open Graph Meta Tags -->
	<meta property="og:title" content="Abdur Rehman Shaikh | Portfolio">
	<meta property="og:description" content="The portfolio of Abdur Rehman Shaikh, showcasing projects and skills in web development and software engineering.">
	<meta property="og:type" content="website">
	<meta property="og:url" content="https://abdurrahmanshkh.pages.dev/">
	<meta property="og:image" content="https://lh3.googleusercontent.com/pw/AP1GczOLf6CMT4K1OOWjVI82HSCdSDGyWKPdQFTibakpujXxZMUbcpSUacpbejtPZ4bNDfAdNUez5dNgxTogyJV2k2aAHKeHmDDezB7Hb3bjdWhBnWK3rtkNkZ9mot_brX2L7vuIL-Dz4kT11LbaFYcQ4Nq_HxrsCuumCz4wZE8ggc9SYqTjsiJ7NALMfiwfTxBP0jlE1Ykc4Wpl2MfyODY5EIi0_lXWw_oAMUhu6BHArVEvJDF9vxO4aPunMHjsn9qI-VC2QAx8vEu5FqTes34zhHV6IhVMXyfbZ0YtApurP02B6VqMkib_JqhhrXjIkZzWJAKmRQRd6pyr8VUuwoJA0QOCUXTLXyOXvN5MmlfvxNoeTGKTcJOrzejPPyWl4jB70fKkwjKEe1kooojuojuf23Lgh3qYSXDcxfS2UytEQe6oukIz6wgkAYbrXiozUrovLZpLxfY6CqN0rt50UBXMHmx7OMDNxyiNV3N61IBuxJeLWud2WaoX128X6tpCHVCKwc8luFOQUfc1dEPkI9fh5huVn5fJ42axBvZ3hLbApKpymWtUxX3f8r6a2vJrs2zB7QnPVoN95SsbyKH3Bx_8yXwukGN8EskA6s_-VR9DBys5GAXg0trnFzXC6IuSJ6UPvm9vmBqMecqHTuJLpo3yWZ4nGp8aKFypNfeVB8P9RXXobRnOYDv8y8QIfJxfJHmVMWkZW3feAcUtQVUMnOzzHJQEk14e7fG9VpaATH3IQK9sMAICeLV43jbJnYrVOst4IAwHuCejPHfhGtKlNaiKLzsm3OGl8tufn-0_BAYiyn96a-y8zyAiYT6Y4OqXnW3t8Jvufttqkl6KhXwZUv3kaPl5dqrflA4kWNUPC26ggFkKMaWwZ1gfLzMgNf7wjJIcBCp62pqQqZEj66pyiaEOY6mVbLTmOHnVCxAs-gxTy110SB1-9WmsCrb4epr40n8Z5fiFJ-zE8J8MNwfMUOKs3pNMpiGhmrKIkvgeR5hNVk_bSrasqUyq3uEUgPJxRXagrlkhhQ=w673-h897-s-no-gm?authuser=0">
	<!-- Twitter Card Meta Tags -->
	<meta name="twitter:card" content="summary_large_image">
	<meta name="twitter:title" content="Abdur Rehman Shaikh | Portfolio">
	<meta name="twitter:description" content="The portfolio of Abdur Rehman Shaikh, showcasing projects and skills in web development and software engineering.">
	<meta name="twitter:image" content="https://lh3.googleusercontent.com/pw/AP1GczOLf6CMT4K1OOWjVI82HSCdSDGyWKPdQFTibakpujXxZMUbcpSUacpbejtPZ4bNDfAdNUez5dNgxTogyJV2k2aAHKeHmDDezB7Hb3bjdWhBnWK3rtkNkZ9mot_brX2L7vuIL-Dz4kT11LbaFYcQ4Nq_HxrsCuumCz4wZE8ggc9SYqTjsiJ7NALMfiwfTxBP0jlE1Ykc4Wpl2MfyODY5EIi0_lXWw_oAMUhu6BHArVEvJDF9vxO4aPunMHjsn9qI-VC2QAx8vEu5FqTes34zhHV6IhVMXyfbZ0YtApurP02B6VqMkib_JqhhrXjIkZzWJAKmRQRd6pyr8VUuwoJA0QOCUXTLXyOXvN5MmlfvxNoeTGKTcJOrzejPPyWl4jB70fKkwjKEe1kooojuojuf23Lgh3qYSXDcxfS2UytEQe6oukIz6wgkAYbrXiozUrovLZpLxfY6CqN0rt50UBXMHmx7OMDNxyiNV3N61IBuxJeLWud2WaoX128X6tpCHVCKwc8luFOQUfc1dEPkI9fh5huVn5fJ42axBvZ3hLbApKpymWtUxX3f8r6a2vJrs2zB7QnPVoN95SsbyKH3Bx_8yXwukGN8EskA6s_-VR9DBys5GAXg0trnFzXC6IuSJ6UPvm9vmBqMecqHTuJLpo3yWZ4nGp8aKFypNfeVB8P9RXXobRnOYDv8y8QIfJxfJHmVMWkZW3feAcUtQVUMnOzzHJQEk14e7fG9VpaATH3IQK9sMAICeLV43jbJnYrVOst4IAwHuCejPHfhGtKlNaiKLzsm3OGl8tufn-0_BAYiyn96a-y8zyAiYT6Y4OqXnW3t8Jvufttqkl6KhXwZUv3kaPl5dqrflA4kWNUPC26ggFkKMaWwZ1gfLzMgNf7wjJIcBCp62pqQqZEj66pyiaEOY6mVbLTmOHnVCxAs-gxTy110SB1-9WmsCrb4epr40n8Z5fiFJ-zE8J8MNwfMUOKs3pNMpiGhmrKIkvgeR5hNVk_bSrasqUyq3uEUgPJxRXagrlkhhQ=w673-h897-s-no-gm?authuser=0">
</svelte:head>

<div class="app">

	<Header />

	<main class="bg-gray-200  dark:bg-gray-900" style="min-height: calc(100vh - 145px);">
		<slot />
	</main>

	<Footer />

</div>
