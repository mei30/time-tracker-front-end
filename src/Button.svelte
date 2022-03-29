<script lang="ts">
    import { onMount } from "svelte";
    import {MDCRipple} from '@material/ripple';

    onMount(() => {
        const buttonRipple = new MDCRipple(document.querySelector('.mdc-button'));
        console.log("fffffffffffffffffffffffffffffffffff");
    })

</script>
<button class="mdc-button">
  <span class="mdc-button__ripple"></span>
  <span class="mdc-button__label">Text Button</span>
</button>