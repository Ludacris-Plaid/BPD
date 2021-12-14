<template>
  <div id="header-box">
    <div id="inner-box-1">
      <img
        src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.explicit.bing.net%2Fth%3Fid%3DOIP.Fkh1-mXt4TFviqCoIg5EfQHaEK%26pid%3DApi&f=1"
      />
    </div>
    <div id="inner-box-2">
      <h1>The BlackPill Diaries</h1>
      <p>Tales From The Clownworld</p>
    </div>
    <div id="inner-box-3">
       <img
        src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.explicit.bing.net%2Fth%3Fid%3DOIP.Fkh1-mXt4TFviqCoIg5EfQHaEK%26pid%3DApi&f=1"
      />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#header-box {
  height: 15 vh;
  width: 100%;
  border: 5px solid black;
  border-radius: 10px;
  display: grid;
  grid-template-columns: 1fr 3fr 1fr;
}
#inner-box-2 {
  background-color: #91a1ba;
}
#inner-box-3 {
  background-color: #91a1ba;
}
img {
  height: 100%;
  width: 100%;
}
h1 {
  text-align: center;
  font-size: 8vh;
  font-family: "Permanent Marker", cursive;
}
p {
  text-align: center;
  font-family: "Bebas Neue", cursive;
  font-size: 4vh;
}
@media screen and (min-width :400px){
  #header-box {
    display: inline-flex;

  }
  img {
    display: none;
  }
}
</style>