<script lang="ts">

    import { page } from '$app/state'; 
    import { base } from '$app/paths';

</script>

<header>
    <div class="logo">Ethan Hawkins </div>
    <nav>
        <a href="{base}/" class={page.url.pathname === base + "/" || page.url.pathname === base ? 'active' : ''}>About Me</a>
        <a href="{base}/projects" class={page.url.pathname === base + "/projects" ? 'active' : ''}>Projects</a>
        <a href="{base}/blog" class={page.url.pathname === base + "/blog" ? 'active' : ''}>Blog</a>
        <a href="{base}/employment" class={page.url.pathname === base + "/employment" ? 'active' : ''}>Employment</a>
    </nav>
</header>
  
<main>
</main>
