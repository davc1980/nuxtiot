<template>
  <div class="container-fluid">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <div class="card m-3 col-2">
      <h1>hi dav</h1>
      <nuxt-link to="/about">About</nuxt-link>
      <a href="https://www.iot-solutions.com.mx">IoT Solutions</a>
      <button class="btn-primary m-4" onclick="window.print();">Print this page</button>
      <a href="/texto.txt" download>download</a>
      <a href="/coti.pdf" download>download cotizacion</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
