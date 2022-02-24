<template>
  <div class="header">
    <h2>My Contact Book</h2>
    <nav>
      <ul>
        <li>
          <a>Home</a>
        </li>
        <li>
          <a>Add New</a>
        </li>
        <li>
          <a>View All</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'HeaderTop',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
li{
  list-style-type: none;
}
ul{
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  padding:0px
}


</style>