<script setup>
//attribute binding
const mydataid = "id1";
// dynamically binding multiple attribute
const obj = {
  id: "box",
  href: "https://www.w3schools.com",
};
// dynamic arguments
const ref = "href";
const url = "https://www.tuiost.edu.np";
// boolean attribute
const isDisabled = false;
</script>
<template>
  <div>
    <h1 :id="mydataid">this is first heading</h1>
    <a v-bind="obj">w3schools</a><br />
    <a v-bind:[ref]="url">this is official link of science and technology</a
    ><br />
    <button :disabled="isDisabled">click here</button>
  </div>
</template>
<style scoped></style>
