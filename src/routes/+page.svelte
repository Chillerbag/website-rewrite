<script lang="ts">

    import { page } from '$app/state'; 

</script>

<header>
    <div class="logo">Ethan Hawkins </div>
    <nav>
        <a href="/" aria-current={page.url.pathname === "/"}>About Me</a>
        <a href="/projects" aria-current={page.url.pathname === "/projects"}>Projects</a>
        <a href="/blog" aria-current={page.url.pathname === "/blog"}>Blog</a>
        <a href="/employment" aria-current={page.url.pathname === "/employment"}>Employment</a>
    </nav>
</header>
  
<main>
    <slot><button class="btn w-64 rounded-full">Button</button></slot>
</main>
