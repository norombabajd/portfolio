<script>
    import zotology from '$lib/assets/projects/zotology.png';
    import { OpenOutline } from 'svelte-ionicons';


</script>

<div class="flex justify-center items-center p-2 mt-3 ml-3 mr-3 rounded-lg bg-gradient-to-l from-[#0064a4] to-[#1b3d6d]">
    <div class="flex flex-col items-center text-center m-5 text-[#EBFFF8]">
        <img draggable="false" class="h-48" alt="A dashboard containing information like enrollment window, upcoming events, and course planning." src={zotology} />

        <div class="mt-5">
            <p class="text-sm font-light">THIRD PLACE OVERALL</p>
            <a href='https://github.com/johnlorenzini/zotology' class="flex space-x-2 justify-center items-center">
                <h1 class="lg:text-2xl text-lg font-semibold">WebReg, reimagined by Zotology</h1>
                <OpenOutline color='#EBFFF8'/>
            </a>
            <p class="mb-5">A detail oriented student-enrollment experience.</p>
        </div>

        

    </div> 
</div>

