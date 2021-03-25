<template>
  <div class="container">
    <div>
      <h1 class="title">
        Welcome to Lucie's Aircall Use Case
      </h1>
      <div class="grid">
        <FirstQuestion />
        <SecondQuestion />
        <ThirdQuestion />
        <FourthQuestion />
      </div>
      <p class="footnote">Thanks for reading my use case !</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
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
  font-weight: 100;
  font-size: 60px;
  color: rebeccapurple;
  letter-spacing: 1px;
  margin-bottom: 100px;
  margin-top: 100px;
}

.subtitle {
  font-weight: 80;
  font-size: 36px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 5px;
}

.footnote {
  font-weight: 120;
  font-size: 42px;
  word-spacing: 5px;
  padding-top: 100px;
  padding-bottom: 150px;
  color: rebeccapurple;
}
</style>
