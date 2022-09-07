<page>
    <actionBar title="page 1" />
    
    <flexboxLayout flexDirection="column">
	    <label class="info" text={message} />
      <button text="Back Home" on:tap="{goBack}" />
    </flexboxLayout>
</page>

<script>
    import { goBack } from 'svelte-native'
</script>

<style>
    
</style>
