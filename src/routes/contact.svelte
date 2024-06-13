<script>
	import { Card, Hr, Button } from 'flowbite-svelte';
	import { Dropdown, DropdownItem } from 'flowbite-svelte';
	import { ChevronDownOutline } from 'flowbite-svelte-icons';
	import { Listgroup, ListgroupItem, } from 'flowbite-svelte';
	import { DownloadOutline, EnvelopeOutline, FilePdfOutline, GithubSolid, LinkedinSolid, PaperPlaneOutline, WhatsappSolid } from 'flowbite-svelte-icons';

	function openLinkedIn() {
		window.open("https://www.linkedin.com/in/abdurrahmanshkh/", "_blank");
	}

	function openGitHub() {
		window.open("https://github.com/abdurrahmanshkh", "_blank");
	}

	function openEmail() {
		window.open("mailto:as31@somaiya.edu", "_blank");
	}

	function openWhatsApp() {
		window.open("https://api.whatsapp.com/send?phone=919653332540", "_blank");
	}

	function openTelegram() {
		window.open("https://t.me/abdurrahmanshkh", "_blank");
	}

	function openViewResume() {
		window.open("https://somaiya0-my.sharepoint.com/:b:/g/personal/as31_somaiya_edu/EVAiSyh5Wa9CiYXg-Nl5HA8BBOzgPv-1O1WuowxGRUNW0Q", "_blank");
	}

	function openDownloadResume() {
		window.open("https://somaiya0-my.sharepoint.com/personal/as31_somaiya_edu/_layouts/15/download.aspx?SourceUrl=%2Fpersonal%2Fas31%5Fsomaiya%5Fedu%2FDocuments%2FPortfolio%2FResume%2Epdf", "_blank");
	}

</script>

<Card class="border-2 border-gray-300 dark:border-gray-700" size="" padding="xl">
<div class="grid grid-cols-1 gap-10">

	<Listgroup active class="w-40 border-2 border-gray-300 dark:border-gray-700">
		<h3 class="p-2 text-center text-2xl font-semibold text-gray-900 dark:text-gray-100">Resume</h3>
		<ListgroupItem class="text-base font-semibold gap-2 py-2.5 text-gray-700 dark:text-gray-300" on:click={openViewResume}>
			<FilePdfOutline/>View
		</ListgroupItem>

		<ListgroupItem class="text-base font-semibold gap-2 py-2.5 text-gray-700 dark:text-gray-300" on:click={openDownloadResume}>
			<DownloadOutline/>Download
		</ListgroupItem>

	</Listgroup>

	<Listgroup active class="w-40 border-2 border-gray-300 dark:border-gray-700">
		<h3 class="p-2 text-center text-2xl font-semibold text-gray-900 dark:text-gray-100">Contact</h3>

		<ListgroupItem class="text-base font-semibold gap-2 py-2.5 text-gray-700 dark:text-gray-300" on:click={openLinkedIn}>
			<LinkedinSolid/>LinkedIn
		</ListgroupItem>

		<ListgroupItem class="text-base font-semibold gap-2 py-2.5 text-gray-700 dark:text-gray-300" on:click={openGitHub}>
			<GithubSolid/> GitHub
		</ListgroupItem>

		<ListgroupItem class="text-base font-semibold gap-2 py-2.5 text-gray-700 dark:text-gray-300" on:click={openEmail}>
			<EnvelopeOutline/> Email
		</ListgroupItem>

		<ListgroupItem class="text-base font-semibold gap-2 py-2.5 text-gray-700 dark:text-gray-300" on:click={openWhatsApp}>
			<WhatsappSolid/> WhatsApp
		</ListgroupItem>

		<ListgroupItem class="text-base font-semibold gap-2 py-2.5 text-gray-700 dark:text-gray-300" on:click={openTelegram}>
			<PaperPlaneOutline/> Telegram
		</ListgroupItem>
	</Listgroup>
</div>		
</Card>
