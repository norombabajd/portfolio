<script>
//   import profilephoto from '$lib/assets/branding/johndaniel.jpg';
  import { LogoGithub, LogoInstagram } from 'svelte-ionicons';
  import { blur } from 'svelte/transition'  
  import { onMount } from 'svelte';

    let ready = false;
    onMount(() => ready = true);

</script>

{#if ready}
<header in:blur="{{delay: 100}}" class="">
    <div class="flex justify-between items-center max-h-48 p-2 mt-3 ml-3 mr-3 rounded-lg bg-[#EBFFF8] shadow-white">
        <div class="flex items-center mr-2">
            <!-- <img class="w-8 rounded-full justify-center" alt="John Daniel wearing a blue polo and glasses, behind a background of sky and bushes." src={profilephoto} /> -->
            <p class="text-2xl font-medium text-[#131216] px-2"><a href="https://norombabajd.com">John Daniel</a></p>
        </div>
    
        <div class="flex space-x-5 mr-2">
            <a href="https://instagram.com/norombabajd"><LogoInstagram color="#131216"/></a>
            <a href="https://github.com/norombabajd"><LogoGithub color="#131216"/></a>
        </div>

    </div>
</header>
{/if}