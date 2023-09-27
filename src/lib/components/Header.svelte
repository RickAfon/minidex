<script lang="ts">
    
</script>
<header>
    <nav class="header-grid-container">
        <h1 class="logo">Minidex</h1>
        <div class="gen-selector">
            <div class="">
                <label for="region" class="">Region</label>
                <fieldset class="rg-filter-option">
                    <input type="checkbox" name="region" id="rg-all" class=""><label for="rg-all">All</label>
                </fieldset>
                <fieldset class="rg-filter-option">
                    <input type="checkbox" name="region" id="rg-kanto" class=""><label for="rg-kanto">Kanto</label>
                </fieldset>
                <fieldset class="rg-filter-option">
                    <input type="checkbox" name="region" id="rg-johto" class=""><label for="rg-johto">Johto</label>
                </fieldset>
                <fieldset class="rg-filter-option">
                    <input type="checkbox" name="region" id="rg-hoenn" class=""><label for="rg-hoenn">Hoenn</label>
                </fieldset>
                <fieldset class="rg-filter-option">
                    <input type="checkbox" name="region" id="rg-sinnoh" class=""><label for="rg-sinnoh">Sinnoh</label>
                </fieldset>
                <fieldset class="rg-filter-option">
                    <input type="checkbox" name="region" id="rg-unova" class=""><label for="rg-unova">Unova</label>
                </fieldset>
            </div>
        </div>
        <div class="search">a</div>
    </nav>
</header>
<style>
    .header-grid-container {
        background-color: #c02716;
        display: grid;
        grid-template-columns: 1fr 5fr 1fr;
        align-content: space-evenly;
        align-items: center;
        justify-content: center;
        column-gap: 0.3rem;
        min-height: 5.5rem;
        padding: 0.5rem;
    }
    .logo {
        font-size: 3rem;
        background-color: red;
    }
    .gen-selector {
        display: inline-flex;
        justify-content: space-between;
        background-color: blue;
    }
    .rg-filter-option {
        display: inline-flex;
        align-items: center;
    }
    .search {
        background-color: green;
    }
</style>
