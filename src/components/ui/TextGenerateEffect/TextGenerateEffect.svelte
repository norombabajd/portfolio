<script lang="ts">
	import { Motion } from 'svelte-motion';
	import { cn } from '$lib/cn';

	export let words: string;
	export let className: string | undefined = undefined;

	const variants = {
		visible: (i: number) => ({
			opacity: 1,
			transition: {
				delay: i * 0.2,
				duration: 1
			}
		}),
		hidden: { opacity: 0.25 }
	};
</script>

<div class={cn('', className)}>
	<div class="">
		<div class="flex justify-center text-2xl font-normal text-black dark:text-white">
			<Motion let:motion custom={0} {variants} initial="hidden" animate={'visible'}>
				<div use:motion>
					{#each words.split(' ') as word, idx (`${word}${idx}`)}
						<Motion let:motion {variants} custom={idx + 1} initial="hidden" animate={'visible'}>
							<span use:motion class="text-white dark:text-white">
								{word}{' '}
							</span>
						</Motion>
					{/each}
				</div>
			</Motion>
		</div>
	</div>
</div>