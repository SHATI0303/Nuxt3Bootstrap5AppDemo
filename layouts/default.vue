<template>
  <div>
    <Mycomponent />
    <slot />

  </div>
</template>
<style>
body {
  background-color: #f5f5dc;
 }

table {
  border-collapse: collapse;
  width: 50%;
}

th, td {
  border: 1px solid black;
  padding: 8px;
  text-align: left;
}

th {
  background-color: #f2f2f2;
}
</style>