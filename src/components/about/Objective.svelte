<script>
    import { OpenOutline } from 'svelte-ionicons';
    import johndaniel from '$lib/assets/branding/johndaniel-standing.webp';
    import { TextGenerateEffect } from '../../components/ui/TextGenerateEffect';
    const words = 'At a young age, I was passionate about helping my community and grew a deep affection for technology. Now, I leverage my technical skills to create ideas and solutions that are people-driven. And use my social skills to empower others and to share my own experiences as a UC Irvine student.';
</script>


<div class="lg:w-2/3 flex justify-align items-center pt-2 mt-3 ml-3 mr-3 rounded-lg bg-gradient-to-l from-[#872224] to-[#792622]">
    <div class="flex flex-col items-left text-left m-10">
        <TextGenerateEffect {words} />
        <a href='https://read.cv/johndaniel'class="flex pt-5 space-x-2 justify-left items-center">
            <p class="text-[#EBFFF8]">Curriculum Vitae</p>
            <OpenOutline color='white'/>
        </a>
    </div> 
</div>