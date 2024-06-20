<script>
    import Headline from '../components/about/Headline.svelte';
    import Objective from '../components/about/Objective.svelte';
    import WebReg from '../components/projects/WebReg.svelte';
    import DailySmirk from '../components/projects/DailySmirk.svelte';
    import Portfolio from '../components/projects/Portfolio.svelte';
    import Threads from '../components/explore/Threads.svelte';
    import Spotify from '../components/explore/Spotify.svelte';
</script>

<div>
    <!-- About -->
    <div>
        <div class="lg:flex h-1/3">
            <Headline/>
            <Objective/>
        </div>
    </div>
    <!-- Projects -->
    <div>
        <div class="grid lg:grid-cols-2">
            <DailySmirk/>
            <WebReg/>
        </div>
    </div>
    <!-- Explore -->
    <hr class="lg:hidden w-48 h-1 mx-auto mt-5 mb-2 bg-gray-100 border-0 rounded dark:bg-gray-700">
    <div>
        <div class="grid lg:grid-cols-3">
            <Threads/>
            <Spotify/>
            <Portfolio/>
        </div>
    </div>
</div>