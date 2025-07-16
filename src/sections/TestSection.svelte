


<script>
    import Scroller from "../lib/Scroller.svelte";
    import ArticleText from "../lib/ArticleText.svelte";
</script>


<div>
    <Scroller layout="left">
    <!-- svelte-ignore block_empty -->
    {#snippet sticky()}
    <img class="duck-img" src="sun.png" alt="Sun" />
    {/snippet}

    {#snippet scrolly()}
        <ArticleText>

                Here is a <strong>cool</strong> sun picture I found.
            
        </ArticleText>
         <ArticleText>

                Dope things.
            
        </ArticleText>
        <ArticleText>

               Hard to figure out though.
            
        </ArticleText>
    {/snippet}
</Scroller>
</div>

<style>
    .duck-img {
        width: 25%;
        margin: 0px auto;
    }
</style>