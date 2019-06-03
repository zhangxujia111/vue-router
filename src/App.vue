<template>
  <div id="app">
    <div id="nav">
          <router-link to="/">logo</router-link> 
          <router-link to="/about">about</router-link>
          <router-link to="/chat">chat</router-link>
    </div>
    <div id="content">
      <router-view/>
    </div>
    <div id="footer">
      <footer>footer</footer>
    
    </div>
  </div>
</template>
<script>

</script>


<style lang="scss">
*{
  padding:0 ;
  margin: 0;
}
#app{
  width: 100%;
  height: 80px;
  background-color:green;
  text-align:center;
  color: #2c3e50;
}
#footer{
  height: 50px;
  line-height: 50px;
  background-color: #8b8b8b;
}
#content{
  background-color: #b9e2d0;
  height:600px;
}
#nav{
    width: 50%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    padding: 30px;
}

</style>
