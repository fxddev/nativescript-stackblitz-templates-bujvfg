<page>
    <actionBar title="Home" />
    
    <flexboxLayout flexDirection="column">
	    <label class="info" text={message} />
        <button text="Next page 1"  on:tap="{ () => navigate({ page: PageOne }) }" />
    </flexboxLayout>
</page>

<script>
	import { navigate } from 'svelte-native'
    import PageOne from './Page1.svelte'

    let message = "Hellow worlds"
    
</script>

<style>
    .info {
        font-size: 20;
        horizontal-align: center;
        vertical-align: center;
    }
</style>
