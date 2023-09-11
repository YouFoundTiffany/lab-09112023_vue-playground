<template>
  <div class="expression-exercises container">
    <div class="row">
      <div class="col-12">
        <h1>Exercises</h1>
        <div class="border p-1">
          <p>
            Write a math equation Vue can evaluate, inside of the curly braces
            below:
          </p>

          <p>{{ 2 + 2 }}</p>
        </div>
        <div class="border p-1">
          <p>
            Use interpolation to get the customary Hello, World! to display on
            the screen. Don't forget your quotes
          </p>
          <p>{{ greeting }}</p>
        </div>
      </div>
    </div>
  </div>
</template>
<!-- REVIEW How was I supposed to do hello world? -->
<script>
export default {
  data() {
    return {
      greeting: "hello world"
    }
  }
}


</script>