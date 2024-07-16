<script>
	import { Timeline, TimelineItem } from 'flowbite-svelte';
	import { AccordionItem } from 'flowbite-svelte';
</script>

<div class="border-b-2 border-gray-300 dark:border-gray-700" id="education">
	<AccordionItem>
		<span slot="header" class="text-2xl font-semibold text-gray-900 dark:text-white">Education</span>
		<Timeline>
			<TimelineItem title="KJ Somaiya Institute of Technology, Sion, Mumbai" date="2022-2026">
				<p class="text-base font-bold text-gray-700 dark:text-gray-300">
					B. Tech in Information Technology
				</p>
			</TimelineItem>
			<TimelineItem title="Ramsheth Thakur Public School, Kharghar, Navi Mumbai" date="March 2022">
				<p class="text-base font-bold text-gray-700 dark:text-gray-300">
					Higher Secondary Certification (HSC) | Grade: 81%
				</p>
			</TimelineItem>
			<TimelineItem title="Ramsheth Thakur Public School, Kharghar, Navi Mumbai" date="March 2020">
				<p class="text-base font-bold text-gray-700 dark:text-gray-300">
					Senior Secondary Certification (SSC) | Grade: 96%
				</p>
			</TimelineItem>
		</Timeline>
	</AccordionItem>
</div>