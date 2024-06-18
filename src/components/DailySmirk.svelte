<script>
    import smirks from '$lib/assets/projects/smirks.png';
    import { LogoGithub, Easel } from 'svelte-ionicons';

</script>

<div class="flex justify-center items-center p-2 mt-3 ml-3 mr-3 rounded-lg bg-gradient-to-l from-[#FFFFFF] to-[#ebf8ff]">
  <div class="flex flex-col items-center text-center m-5 text-[#131216]">
    <p class="text-sm font-light">FEATURED PROJECT</p>
    <h1 class="text-2xl font-semibold">The Daily Smirk</h1>
    <img class="w-96 pt-5 pb-5" alt="Five smiley-faces representing different emotions from fluttered to annoyed." src={smirks} />
    <p class="mb-5 lg:pl-24 lg:pr-24">High frequency peer-assessments made easy. UI, UX, and Front-end development, under Professor Andre Van Der Hoek & Yu Lu, Department of Informatics at UCI.</p> 
    <div class="flex space-x-2">
      <a href='https://yulyalu.github.io/Daily-Smirk-Website/' class="px-8 py-2 rounded-full bg-gradient-to-b from-blue-500 to-blue-600 text-white focus:ring-2 focus:ring-blue-400 hover:shadow-xl transition duration-200">
          Learn more
      </a>
        <a href='https://www.linkedin.com/posts/norombabajd_when-working-in-groups-for-class-projects-activity-7197725356898861056-XhSO?utm_source=share&utm_medium=member_desktop' class="px-2 py-2 rounded-full outline outline-blue-500 focus:ring-2 focus:ring-blue-400 hover:shadow-xl transition duration-200">
          <Easel color='#3b82f6'/>
        </a>
    </div>
  </div> 
</div>
