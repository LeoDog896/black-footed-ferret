<script lang="ts">
    const links = [
        "https://www.worldwildlife.org/species/black-footed-ferret",
        "https://nationalzoo.si.edu/animals/black-footed-ferret",
        "https://www.fws.gov/species/black-footed-ferret-mustela-nigripes",
        "https://www.nationalgeographic.com/animals/mammals/facts/black-footed-ferret",
        "https://www.nps.gov/articles/000/black-footed-ferret-badl.htm",
        "https://defenders.org/wildlife/black-footed-ferret"
    ]
</script>

<h1>Sources</h1>

<ul>
    {#each links as link}
        <li><a href={link}>{link}</a></li>
    {/each}
</ul>