<script>
  export let router = {};
  let id = null;

  $: {
    id = router.params ? router.params.id : null;
  }
</script>

<h1>Post ID: {id}</h1>
