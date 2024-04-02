<script>
    let audio;
    
    const playAudio = () => {
      audio.play();
    };
</script>

<body class="background text-white md:text-black">
    <div class="p-10">
        <p class="text-7xl md:text-9xl gtaFont">$MIAMI Coin</p>
        <p class="text-3xl md:text-5xl py-6">Official Meme Coin of the City of <br> Miami, Florida</p> 
        <button on:click={playAudio} class="outrun-button">Vibe</button> 
        <audio src="/She.mp3" bind:this={audio}></audio>
    </div>
    <div class="h-lvh flex items-center gap-2 md:gap-9 justify-center">
        <a class="outrun-button" href="https://twitter.com/tickermiami" target="_blank">Telegram</a>
        <a class="outrun-button" href="https://twitter.com/tickermiami" target="_blank">Twitter</a>
        <a class="outrun-button" href="https://dexscreener.com/solana/cqjwxq3te3d961qbjlvq6sftzvvmepyqlwp9ryp5wpxg" target="_blank">Chart</a>
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