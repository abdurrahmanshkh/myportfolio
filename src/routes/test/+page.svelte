<script>
  import {Listgroup } from "flowbite-svelte";
  import { DownloadSolid, EnvelopeOpenSolid, FilePdfSolid, GithubSolid, LinkedinSolid, PaperPlaneSolid, WhatsappSolid } from 'flowbite-svelte-icons';
  let icons = [
    { name: 'LinkedIn', icon: LinkedinSolid },
    { name: 'GitHub', icon: GithubSolid },
    { name: 'Email', icon: EnvelopeOpenSolid },
    { name: 'WhatsApp', icon: WhatsappSolid},
    { name: 'Telegram', icon: PaperPlaneSolid},
    { name: 'View Resume', icon:FilePdfSolid},
    { name: 'Download Resume', icon: DownloadSolid},
  ];
  // <svelte:component this={IconSolid} icon={item.icon} class="w-3 h-3 me-2.5" />
</script>


<Listgroup active items={icons} let:item class="w-48" on:click={console.log}>
  <svelte:component this={item.icon} class="w-4 h-4 me-2.5"/>
  {item.name}
</Listgroup>