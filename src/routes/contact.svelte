<script>
	import { Card, Hr, Button } from 'flowbite-svelte';
	import { Dropdown, DropdownItem } from 'flowbite-svelte';
	import { ChevronDownOutline } from 'flowbite-svelte-icons';
</script>

<Card class="border-2 border-gray-300 dark:border-gray-700" size="" padding="xl" id="contact">
	<h5 class="text-2xl font-bold text-gray-900 dark:text-white">Contact</h5>
	<Hr classHr="my-5 h-1" />
	<div class="max-w-screen-xl items-center gap-5 lg:grid lg:grid-cols-6">
		<Button
			href="https://www.linkedin.com/in/abdurrahmanshkh/"
			target="_blank"
			class="m-0 border-2 border-gray-500 px-1.5 py-1.5 dark:border-gray-500"
			color="light"
		>
			<img width="30" height="30" src="src/routes/icons/linkedin.png" alt="LinkedIn" />
			<div class="pl-1">LinkedIn</div>
		</Button>

		<Button
			href="https://github.com/abdurrahmanshkh"
			target="_blank"
			class="m-0 border-2 border-gray-500 px-1.5 py-1.5 dark:border-gray-500"
			color="light"
		>
			<img width="30" height="30" src="src/routes/icons/github.png" alt="GitHub" />
			<div class="pl-1">GitHub</div>
		</Button>

		<Button
			href="mailto:as31@somaiya.edu"
			target="_blank"
			class="m-0 border-2 border-gray-500 px-1.5 py-1.5 dark:border-gray-500"
			color="light"
		>
			<img width="30" height="30" src="src/routes/icons/email.png" alt="Email" />
			<div class="pl-1">Email</div>
		</Button>

		<Button
			href="https://api.whatsapp.com/send?phone=919653332540"
			target="_blank"
			class="m-0 border-2 border-gray-500 px-1.5 py-1.5 dark:border-gray-500"
			color="light"
		>
			<img width="30" height="30" src="src/routes/icons/whatsapp.png" alt="WhatsApp" />
			<div class="pl-1">WhatsApp</div>
		</Button>

		<Button
			href="https://t.me/abdurrahmanshkh"
			target="_blank"
			class="m-0 border-2 border-gray-500 px-1.5 py-1.5 dark:border-gray-500"
			color="light"
		>
			<img width="30" height="30" src="src/routes/icons/telegram.png" alt="Telegram" />
			<div class="pl-1">Telegram</div>
		</Button>

		<Button class="m-0 border-2 border-gray-500 px-1.5 py-1.5 dark:border-gray-500" color="light">
			<img width="30" height="30" src="src/routes/icons/resume.png" alt="Resume" />
			<div class="pl-1">Resume</div>
			<ChevronDownOutline class="ms-0 h-6 w-6 text-white dark:text-white" />
		</Button>
		<Dropdown>
			<DropdownItem
				href="https://somaiya0-my.sharepoint.com/:b:/g/personal/as31_somaiya_edu/EVAiSyh5Wa9CiYXg-Nl5HA8BBOzgPv-1O1WuowxGRUNW0Q"
				target="_blank"
				class=""
				>View
			</DropdownItem>
			<DropdownItem
				href="https://somaiya0-my.sharepoint.com/personal/as31_somaiya_edu/_layouts/15/download.aspx?SourceUrl=%2Fpersonal%2Fas31%5Fsomaiya%5Fedu%2FDocuments%2FPortfolio%2FResume%2Epdf"
				>Download
			</DropdownItem>
		</Dropdown>
	</div>
</Card>
