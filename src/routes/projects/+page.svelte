<script lang="ts">
    import { page } from '$app/state'; 
    import { base } from '$app/paths';
    import { GradientButton, Navbar, NavBrand, NavLi, NavUl, NavHamburger, Card } from 'flowbite-svelte';
    import { GithubSolid, LinkedinSolid, DownloadSolid, ArrowUpRightFromSquareOutline } from 'flowbite-svelte-icons';
</script>

<div class="container mx-auto px-4 max-w-4xl">
    <header>
        <Navbar color='primary'>
            <NavBrand href="{base}/">
                <span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Ethan Hawkins</span>
            </NavBrand>
            <NavHamburger />
            <NavUl>
                <NavLi href="{base}/">Home</NavLi>
                <NavLi href="{base}/projects">Projects</NavLi>
                <NavLi href="{base}/blog">Blog</NavLi>
                <NavLi href="{base}/employment">Employment</NavLi>
            </NavUl>
        </Navbar>
    </header>

    <main class="mt-8">
        <!-- Rust Section -->
        <div class="mb-8">
            <div class="flex items-center mb-4">
                <img src="{base}/Rust.png" class="w-8 h-8 mr-2" alt="Rust" />
                <h3 class="text-xl font-bold dark:text-white">Rust</h3>
                <div class="flex-grow ml-4 border-t border-gray-300 dark:border-gray-600"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <Card>
                    <h5 class="mb-1 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white">Rust-RFC-865-Server</h5>
                    <p class="mb-3 italic text-sm text-gray-600 dark:text-gray-400">March 2025</p>
                    <p class="mb-3 font-normal text-gray-500 dark:text-gray-400">A custom rust server for serving quotes to clients via TCP - with multithreading features!</p>
                    <a href="https://github.com/Chillerbag/Rust-RFC865-Server" class="inline-flex items-center text-primary-600 hover:underline">
                        Github
                        <ArrowUpRightFromSquareOutline class="w-4 h-4 ms-2.5" />
                    </a>
                </Card>
            </div>
        </div>
        
        <!-- JavaScript Section -->
        <div class="mb-8">
            <div class="flex items-center mb-4">
                <img src="{base}/JavaScript.png" class="w-8 h-8 mr-2" alt="JavaScript" />
                <h3 class="text-xl font-bold dark:text-white">JavaScript</h3>
                <div class="flex-grow ml-4 border-t border-gray-300 dark:border-gray-600"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <Card>
                    <h5 class="mb-1 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white">Applyify</h5>
                    <p class="mb-3 italic text-sm text-gray-600 dark:text-gray-400">December 2024</p>
                    <p class="mb-3 font-normal text-gray-500 dark:text-gray-400">Applyify is William Spongberg and I's entry into the Google built in AI Hackathon. It updates your resume on the fly as you look at jobs.</p>
                    <div class="flex flex-wrap gap-3">
                        <a href="https://github.com/Chillerbag/Applyify" class="inline-flex items-center text-primary-600 hover:underline">
                            Github
                            <ArrowUpRightFromSquareOutline class="w-4 h-4 ms-2.5" />
                        </a>
                        <a href="https://youtu.be/A3yoSceNt60" class="inline-flex items-center text-primary-600 hover:underline">
                            Youtube
                            <ArrowUpRightFromSquareOutline class="w-4 h-4 ms-2.5" />
                        </a>
                    </div>
                </Card>
            </div>
        </div>

        <!-- Bash Section -->
        <div class="mb-8">
            <div class="flex items-center mb-4">
                <img src="{base}/Bash.png" class="w-8 h-8 mr-2" alt="Bash" />
                <h3 class="text-xl font-bold dark:text-white">Bash</h3>
                <div class="flex-grow ml-4 border-t border-gray-300 dark:border-gray-600"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <Card>
                    <h5 class="mb-1 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white">Bashlog</h5>
                    <p class="mb-3 italic text-sm text-gray-600 dark:text-gray-400">Feb 2025</p>
                    <p class="mb-3 font-normal text-gray-500 dark:text-gray-400">A program embeded at your PATH to help you manage your backlog!</p>
                    <a href="https://github.com/Chillerbag/logbash" class="inline-flex items-center text-primary-600 hover:underline">
                        Github
                        <ArrowUpRightFromSquareOutline class="w-4 h-4 ms-2.5" />
                    </a>
                </Card>
            </div>
        </div>

        <!-- Lua Section -->
        <div class="mb-8">
            <div class="flex items-center mb-4">
                <img src="{base}/Lua.png" class="w-8 h-8 mr-2" alt="Lua" />
                <h3 class="text-xl font-bold dark:text-white">Lua</h3>
                <div class="flex-grow ml-4 border-t border-gray-300 dark:border-gray-600"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <Card>
                    <h5 class="mb-1 text-2xl font-semibold tracking-tight text-gray-900 dark:text-white">lonely catch</h5>
                    <p class="mb-3 italic text-sm text-gray-600 dark:text-gray-400">March 2025</p>
                    <p class="mb-3 font-normal text-gray-500 dark:text-gray-400">My entry to the CISSA x GMC hackathon. A small game for the Playdate</p>
                    <div class="flex flex-wrap gap-3">
                        <a href="https://github.com/Chillerbag/LonelyCatch" class="inline-flex items-center text-primary-600 hover:underline">
                            Github
                            <ArrowUpRightFromSquareOutline class="w-4 h-4 ms-2.5" />
                        </a>
                        <a href="https://blipity.itch.io/lonely-catch" class="inline-flex items-center text-primary-600 hover:underline">
                            Itch.io
                            <ArrowUpRightFromSquareOutline class="w-4 h-4 ms-2.5" />
                        </a>
                    </div>
                </Card>
            </div>
        </div>
    </main>
</div>