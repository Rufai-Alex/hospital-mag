<script>
	import Howto from './howto.svelte';
	import Timer from './Timer.svelte';
	
	
</script>
<style>
	h1{
		text-align: center;
		text-transform: uppercase;
	}
	h1 span{
		color: red;
	}
	h1 span:hover{
		transform: scale(3);
	}
</style>

<h1>Get Well Hospital</h1>
<Timer/>

<Howto/>  