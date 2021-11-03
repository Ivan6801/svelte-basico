<script>
    let skills = [
        {
            id: 1,
            name: 'HTML'
        },
        { 
            id: 2,
            name: 'CSS'
        },
        {
            id: 3,
            name: 'JavaScript'
        },
        {
            id: 4,
            name: 'React js'
        }
    ];
</script>

<div class="Skills">
    <h3>Habílidades</h3>
    <ul>
    {#each skills as {name}, i}
        <li>{name}</li>
    {/each}
    </ul>
</div>

<style>
    .Skills {
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
    }
    ul {
        margin: 0;
        padding: 0;
        list-style: none;
    }
    li {
        display: inline;
        margin: 0 0 0 0.4rem;
    }
</style>