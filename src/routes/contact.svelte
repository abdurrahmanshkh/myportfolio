<script>
	import { Card, Hr, Button } from 'flowbite-svelte';
	import { Dropdown, DropdownItem } from 'flowbite-svelte';
	import { ChevronDownOutline } from 'flowbite-svelte-icons';
</script>

<Card class="border-2 border-gray-300 dark:border-gray-700" size="" padding="xl" id="contact">
	<h5 class="text-2xl font-semibold text-gray-900 dark:text-white">Contact</h5>
	<Hr classHr="my-5 h-0.5 bg-gray-400 dark:bg-gray-700" />
	<div class="items-center gap-5 lg:grid lg:grid-cols-1">
		<Button
			href="https://www.linkedin.com/in/abdurrahmanshkh/"
			target="_blank"
			class="border-2"
			color="light"
		>
			<img width="30" height="30" src="linkedin.png" alt="LinkedIn" />
			<div class="pl-1">LinkedIn</div>
		</Button>

		<Button
			href="https://github.com/abdurrahmanshkh"
			target="_blank"
			class="border-2"
			color="light"
		>
			<img width="30" height="30" src="github.png" alt="GitHub" />
			<div class="pl-1">GitHub</div>
		</Button>

		<Button
			href="mailto:as31@somaiya.edu"
			target="_blank"
			class="border-2"
			color="light"
		>
			<img width="30" height="30" src="email.png" alt="Email" />
			<div class="pl-1">Email</div>
		</Button>

		<Button
			href="https://api.whatsapp.com/send?phone=919653332540"
			target="_blank"
			class="border-2"
			color="light"
		>
			<img width="30" height="30" src="whatsapp.png" alt="WhatsApp" />
			<div class="pl-1">WhatsApp</div>
		</Button>

		<Button
			href="https://t.me/abdurrahmanshkh"
			target="_blank"
			class="border-2"
			color="light"
		>
			<img width="30" height="30" src="telegram.png" alt="Telegram" />
			<div class="pl-1">Telegram</div>
		</Button>

		<Button class="border-2" color="light">
			<img width="30" height="30" src="resume.png" alt="Resume" />
			<div class="pl-1">Resume</div>
			<ChevronDownOutline class="ms-0 h-6 w-6 text-white dark:text-white" />
		</Button>
		<Dropdown>
			<DropdownItem
				href="https://somaiya0-my.sharepoint.com/:b:/g/personal/as31_somaiya_edu/EVAiSyh5Wa9CiYXg-Nl5HA8BBOzgPv-1O1WuowxGRUNW0Q"
				target="_blank"
				class="px-10 text-center"
				>View
			</DropdownItem>
			<DropdownItem
				href="https://somaiya0-my.sharepoint.com/personal/as31_somaiya_edu/_layouts/15/download.aspx?SourceUrl=%2Fpersonal%2Fas31%5Fsomaiya%5Fedu%2FDocuments%2FPortfolio%2FResume%2Epdf"
				class="px-10 text-center"
				>Download
			</DropdownItem>
		</Dropdown>
	</div>
</Card>
