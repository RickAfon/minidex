<script lang="ts">
    import Header from "../lib/components/Header.svelte";
</script>

<svelte:head>
    <title>MiniDex</title>
</svelte:head>
<div class="all">
    <Header/>
    <main class="content-main">
        <div class="item-select">
            
            <div class="item-select-pokemon">
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                <div class="item-pokemon">
                    Bulbasaur
                </div>
                
            </div>

        </div>
        <div class="content-viewer">
            a
        </div>
    </main>
</div>
<style>

    .content-main {
        background-color: aqua;
        display: grid;
        grid-template-columns: 1.5fr 5fr;
        height: 82.865%;
    }

    .item-select {
        overflow-x: hidden;
        overflow-y: scroll;
        -ms-overflow-style: none;
        scrollbar-width: none; 
    }
    .item-select::-webkit-scrollbar {
        display: none;
    }

    .item-select-pokemon {
        display: flex;
        flex-direction: column;
        padding: 6% 20%;
        text-align: center;
    }

    .item-pokemon {
        padding: 6% 0;
        background-color: greenyellow;
        font-size: 1.5rem;
    }

</style>
