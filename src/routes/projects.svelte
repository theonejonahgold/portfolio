<script context="module">
  import { fetchProjects } from '$lib/utils/tileList'
  import type { Load } from '@sveltejs/kit'

  export const load: Load = async function ({}) {
    const items = await fetchProjects()
    return {
      props: {
        items,
      },
    }
  }
</script>

<script>
  import TileList from '$lib/components/organisms/TileList.svelte'
  import textAnimation from '$lib/actions/textAnimation'

  export let items: ArticleMetadata[]
</script>

<svelte:head>
  <title>Projecten - Jonah Meijers</title>
  <meta
    name="descrtiption"
    content="De projecten waar ik aan werk en heb gewerkt."
  />
</svelte:head>

<main>
  <h1
    use:textAnimation={{
      splitOn: 'letters',
    }}
  >
    Projecten
  </h1>
  <TileList {items} animate="both" />
</main>
