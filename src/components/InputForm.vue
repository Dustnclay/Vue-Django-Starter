<template>
  <div class="form">
    <!-- <h1>{{ msg }}</h1> -->
    <label> 
        Name
        <input name='name' placeholder="Clark Kent"/>
    </label><br/>
    
    <label>
        Phone 
        <input name='phone' placeholder="(123) 555-6789"/>
    </label><br/>

    <label>
        Email
        <input name='email' placeholder="LastSonOfKrypton@dailybugle.com"/>
    </label><br/>

  </div>
</template>

<script>
export default {
  name: 'InputForm'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .form{
        margin-left: 5px;
        text-align: left;
    }
</style>