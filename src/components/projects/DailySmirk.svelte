<script>
    import smirks from '$lib/assets/projects/smirks.png';
    import { OpenOutline, Easel } from 'svelte-ionicons';

</script>

<div class="flex justify-center items-center p-2 mt-3 ml-3 mr-3 rounded-lg bg-gradient-to-l from-[#FFFFFF] to-[#ebf8ff]">
  <div class="flex flex-col items-center text-center m-5 text-[#131216]">
    <p class="text-sm font-light">FEATURED PROJECT</p>
    <a href='https://yulyalu.github.io/Daily-Smirk-Website' class="text-[#131216] flex space-x-2 justify-center items-center">
      <h1 class="text-2xl font-semibold">The Daily Smirk</h1>
      <OpenOutline color='#131216'/>
    </a>
    <img draggable="false" class="w-96 pt-5 pb-5" alt="Five smiley-faces representing different emotions from fluttered to annoyed." src={smirks} />
    <p class="mb-5 lg:pl-24 lg:pr-24">High frequency peer-assessments made easy. UI, UX, and Front-end development, under Professor Andre Van Der Hoek & Yu Lu, Department of Informatics at UCI.</p> 
    <p class="text-sm font-light">REACTJS · FIREBASE · TAILWINDCSS</p>
  </div> 
</div>