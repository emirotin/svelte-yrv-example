<script>
  import { Router, Route } from "yrv";
  import Index from "./Index.svelte";
  import Post from "./Post.svelte";
</script>

<main>
  <Router>
    <Route path="/" exact component={Index} />
    <Route path="/post/:id" exact component={Post} />
  </Router>
</main>
