<template>
  <section class="container">
    <div>
      <!-- <logo /> -->
      <h1 class="title">
        Dave Stacey
      </h1>
      <h2>
        (dev nuxt)
      </h2>
      <div class="links">
        <a
          href="https://github.com/davestacey"
          target="_blank"
          class="button--grey"
        >GitHub
        </a>
      </div>
    </div>
  </section>
</template>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 40px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 32px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
  margin: 0;
}
</style>
