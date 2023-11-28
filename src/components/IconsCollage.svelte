<script lang="ts">
	import GitHub from '$lib/assets/icons/github.svg';
	import Docker from '$lib/assets/icons/docker.svg';
	import Google from '$lib/assets/icons/google.svg';
	import Facebook from '$lib/assets/icons/facebook.svg';
	import React from '$lib/assets/icons/react.svg';
	import Twitter from '$lib/assets/icons/twitter.svg';
	import Vue from '$lib/assets/icons/vue.svg';
	import Python from '$lib/assets/icons/python.svg';
	import Dropbox from '$lib/assets/icons/dropbox.svg';
</script>

<div class="outerdiv">
	<img class="innerdiv" src={GitHub} alt="GitHub" />
	<img class="innerdiv" src={Docker} alt="Docker" />
	<img class="innerdiv" src={Google} alt="Google" />
	<img class="innerdiv" src={Facebook} alt="Facebook" />
	<img class="innerdiv" src={React} alt="React" />
	<img class="innerdiv" src={Twitter} alt="Google" />
	<img class="innerdiv" src={Vue} alt="GitHub" />
	<img class="innerdiv" src={Dropbox} alt="Dropbox" />
	<img class="innerdiv" src={Python} alt="Python" />
</div>

<style>
	.outerdiv {
		display: flex;
		flex-wrap: wrap;
	}

	.innerdiv {
		flex-grow: 1;
		width: 33%;
		height: 33%;
	}
</style>
