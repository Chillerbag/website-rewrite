<script lang="ts">
    import { page } from '$app/state'; 
    import { base } from '$app/paths';
    import { GradientButton, Navbar, NavBrand, NavLi, NavUl, NavHamburger} from 'flowbite-svelte';
    import { GithubSolid } from 'flowbite-svelte-icons';

</script>

<header>
    <Navbar color = 'primary'>
        <NavBrand href="/">
            <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Ethan Hawkins</span>
        </NavBrand>
        <NavHamburger  />
        <NavUl >
          <NavLi href="{base}/">Home</NavLi>
          <NavLi href="{base}/projects">Projects</NavLi>
          <NavLi href="{base}/blog">Blog</NavLi>
          <NavLi href="{base}/employment">Employment</NavLi>
        </NavUl>
    </Navbar>
</header>

<main>
    <GradientButton href="https://github.com/Chillerbag" color="greenToBlue">Checkout my Github <GithubSolid class="w-5 h-5 ms-2" /></GradientButton>
</main>

