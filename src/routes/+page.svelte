<script>
    import Headline from '../components/about/Headline.svelte';
    import Objective from '../components/about/Objective.svelte';
    import WebReg from '../components/WebReg.svelte';
    import DailySmirk from '../components/DailySmirk.svelte';
    
</script>

<div>



<!-- About -->
<div>
    <div class="lg:flex">
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






</div>