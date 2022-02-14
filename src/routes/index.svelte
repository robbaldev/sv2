<script>
  
    let mytitle= 'Ninja Gaming Guides'

    const updateTitle = () => {
        mytitle = "something completely different"
    }
</script>

<div class="index">

    <h2>{mytitle}</h2>
    <p>lorem ipsum I'm baby {mytitle} tacos pour-over street art four dollar toast butcher skateboard migas asymmetrical polaroid 8-bit vegan {mytitle} semiotics helvetica. Squid snackwave sartorial, cred dreamcatcher chambray plaid. Taxidermy beard man braid, occupy flexitarian squid retro hella cornhole tilde humblebrag. Meggings polaroid yr ennui jean shorts kombucha, kale chips biodiesel blue bottle coloring book vegan letterpress swag gluten-free copper mug. Meditation iceland subway tile cray, cloud bread biodiesel readymade gentrify four dollar toast.</p>
    <button on:click={updateTitle}>change the title</button>
    <input type="text" bind:value={mytitle}>
    <a href="/guides">View Guides</a>
    <a href="/about">About</a>
</div>

<style>
.index {
    text-align: center;
    display: block;
    margin: 20px auto;
}

</style>