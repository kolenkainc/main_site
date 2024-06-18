<script>
  import welcome from "$lib/images/svelte-welcome.webp";
  import welcome_fallback from "$lib/images/svelte-welcome.png";
</script>

<svelte:head>
  <title>Kolenka Inc</title>
  <meta name="description" content="Kolenka Inc" />
</svelte:head>

<section>
  <div class="title">
    <div class="text">
      <p>Привет</p>
      <p>Мы — Коленка Инкорпорейтед</p>
    </div>
  </div>
</section>

<style>
  @font-face {
    font-family: Academy;
    src: url("Academy.ttf");
  }

  .title {
    height: 50vh;
    font-family: Academy;
  }

  .text {
    position: relative;
    top: 50%;
    transform: translateY(-50%);
    font-size: 7.4vw;
  }
</style>
