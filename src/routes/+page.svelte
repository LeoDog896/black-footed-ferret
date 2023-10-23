<script lang="ts">
    // TODO: CC-BY https://www.flickr.com/photos/usfwsmtnprairie/26003368476
    import Ferret from "$lib/ferret.jpg"
    // TODO: https://www.flickr.com/photos/nationalzoo/6056771856
    import Ferret2 from "$lib/ferret2.jpg"
</script>

<svelte:head>
	<title>Black-Footed Ferret</title>
</svelte:head>

<div class="hero">
    <h1>the Black-Footed <span class="ferret">Ferret</span></h1>

    <h2>A species <i>almost</i> gone <span class="danger">extinct</span></h2>

    <img src={Ferret} class="one" alt="Black-footed ferret" />
    <img src={Ferret2} class="two" alt="Black-footed ferret" />
</div>

<div class="main-container">
    <main>

        <h2>This <i class="highlight">Mustela Nigripes</i> is a flagship & indicator species</h2>

        <p>It indicates the health of its parent environment, the grasslands, and its main prety, the prarie dog</p>
        <p>and helps over <span class="highlight"><b>130</b></span> species, providing services from population control to eagle food.</p>

        <!-- <ul>
            <li>
                They were declared extinct in 1974, rediscovered in 1981, now there is very little genetic
                diversity
            </li>
            <li>
                Elizabeth Ann is a cloned black-footed ferret as a trailblazer for cloning for conservation
                efforts by Revive & Restore to mitigate inbreeding (and thus inbreeding depression)
            </li>
        </ul> -->

        <h2>But, <span class="danger">what if...</span></h2>
    </main>
</div>

<style>
    .ferret {
        color: #3F84E5;
    }

    .danger {
        color: #EA526F;
    }

    .highlight {
        color: #003E1F;
    }

    .hero {
        display: contents;
    }
    .main-container {
        position: absolute;
        top: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
    }

    main {
        max-width: 800px;
    }

    main h2 {
        font-size: 3rem;
    }

    .hero h1 {
        margin-left: 40px;
        font-size: 5rem;
        margin-top: 1rem;
    }

    img {
        border-radius: 1rem;
        border: 5px solid #85756E;
    }

    img.one {
        position: absolute;
        bottom: 40px;
        right: 40px;
        height: 70vh;
    }

    img.two {
        height: 50vh;
        position: absolute;
        left: 40px;
        top: 150px;
    }

    .hero h2 {
        margin-top: 5rem;
        position: absolute;
        bottom: 40px;
        left: 40px;
        margin-bottom: 0;
    }

    p {
        font-size: 1.5rem;
    }
</style>
