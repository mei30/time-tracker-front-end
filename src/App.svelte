<script lang="ts">
	import Button from './Button.svelte';
	import MainComponent from './MainComponent.svelte';

</script>

<main>
	<MainComponent />
	<Button />
</main>

<style global lang="scss">
	@use "@material/theme" with (
  $primary: #fcb8ab,
  $secondary: #feeae6,
  $on-primary: #442b2d,
  $on-secondary: #442b2d,
);
	@use "@material/button/styles";

	@use "./src/styles/base.scss";
</style>