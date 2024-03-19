<script>
    let audio;
    
    const playAudio = () => {
      audio.play();
    };
</script>

<body class="background text-white md:text-black">
    <div class="p-10">
        <p class="text-7xl md:text-9xl gtaFont">$MIA Coin</p>
        <p class="text-3xl md:text-5xl py-6">Official Meme Coin of the City of <br> Miami, Florida</p> 
        <button on:click={playAudio} class="outrun-button">Vibe</button> 
        <audio src="/She.mp3" bind:this={audio}></audio>
    </div>
    <div class="h-lvh flex items-center gap-2 md:gap-9 justify-center">
        <button class="outrun-button">Telegram</button>
        <button class="outrun-button">Twitter</button>
        <button class="outrun-button">Chart</button>
    </div>

</body>

<style>
    @font-face {
    font-family: gta;
    src: url("/fonts/pricedown/pricedown bl.otf");
    }

    .gtaFont{
        font-family: gta;
    }
</style>