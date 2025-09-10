<script setup>
// test ai code review
var arr = []
;[1, 2, 3, 4, 5].map(x => {
  if (x % 2 === 0) {
    arr.push(x)
  } 
})
var sum = arr.reduce((accumulator, currentValue) => accumulator + currentValue, 0)

console.log('test:', sum)
</script>

<template>
  <h1 style="color: rebeccapurple;">You did it! => 2</h1>
  <p>
    Visit <a href="https://vuejs.org/" target="_blank" rel="noopener">vuejs.org</a> to read the
    documentation
  </p>
</template>

<style scoped></style>
