<script lang="ts">
	import Button from '../components/Button.svelte';
	import Section from '../components/Section.svelte';
	import Showcase from '../components/Showcase.svelte';
</script>

<main>
	<div class="blockcontainer">
		<Section>
			<Showcase
				title="Get to work quickly, wherever you are"
				content="Project IDX gets you into your dev workflow in no time, backed by the security and scalability of Google Cloud. Go from opening your browser to developing an application in a matter of seconds, not days, from anywhere and on any machine."
			/>
		</Section>
		<Section>
			<Showcase
				title="Develop with popular frameworks and languages"
				content="Project IDX makes it easier to start building an app that works across multiple platforms using a variety of templates for popular frameworks, such as Angular, Next.js, React, Svelte, and Flutter, with Python and Go support coming soon. You can also import your existing applications from GitHub, with support for most tech stacks."
				imgPosition="left"
			/>
		</Section>
		<Section>
			<Showcase
				title="Optimize your apps across platforms"
				content="Project IDX lets you preview your full-stack, multiplatform apps as your users would see them, with upcoming support for built-in multi-browser web previews, Android emulators, and iOS simulators."
			/>
		</Section>
	</div>
</main>

<style>
	main {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.blockcontainer {
		max-width: 1200px;
		display: flex;
		flex-direction: column;
		padding: 100px 10px 100px 10px;
		gap: 50px;
	}
</style>
