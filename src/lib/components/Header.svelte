<script lang="ts">
    
</script>
<header>
    <nav class="header-grid-container">
        <h1 class="logo">Minidex</h1>
        <div class="filters">
            <div class="gen-selector">
                <label for="region" class="region">Region</label>
                <div class="gen-selector-sub">
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
        min-width: 5rem;
    }
    .gen-selector:hover {
        position: relative;
        display: block;
        transition: 0.2s;
        background-color: #ffd900;
    }
    .filters {
        display: flex;
        justify-content: space-between;
        background-color: blue;
    }
    .gen-selector-sub {
        display: none;
        min-width: inherit;
        position: fixed;
        align-items: center;
    }
    .gen-selector:hover>.gen-selector-sub {
        display: block;
        background-color: #2ddee4;
    }
    .rg-filter-option {
        align-items: center;
    }
    .search {
        background-color: green;
    }
</style>
