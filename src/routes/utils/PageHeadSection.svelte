<script lang="ts">
  import { Heading } from 'flowbite-svelte';
  import CompoDescription from './CompoDescription.svelte';

  export let dir: string;
  export let breadcrumb_title: string;
  export let title: string;
  export let description: string;

  /* eslint-disable  @typescript-eslint/no-unused-expressions */
  dir;
  breadcrumb_title;
</script>

<div class="pb-8">
  <Heading class="inline-block mb-2 font-extrabold tracking-tight text-gray-900 dark:text-white" tag="h1" customSize="text-3xl">
    {title}
  </Heading>

  <CompoDescription>{description}</CompoDescription>
</div>
