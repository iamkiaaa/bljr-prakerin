<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      SMK Telkom Makassar adalah Sekolah Menengah Kejuruan Pusat Keunggulan
    </p>
    <hr>
    <h3>Address</h3>
    <ul>
      <li>Jl. A. P. Pettarani No.4, Gn. Sari, Kec. Rappocini, Kota Makassar, Sulawesi Selatan 90221</li><br>
      <li><a href="https://www.google.com/maps/place/SMK+TELKOM+Makassar/@-5.1712763,119.4341976,17z/data=!3m1!4b1!4m6!3m5!1s0x2dbee32da1a075d3:0x88e9cc6030cfa1dd!8m2!3d-5.1712763!4d119.4363863!16s%2Fg%2F11hzz54gmz" target="_blank" rel="noopener">Maps</a></li>
    </ul>
    <h3>Contact</h3>
    <ul>
      <li>Follow us to know more about SMK TELKOM MAKASSAR</li><br>
      <li><a href="https://www.instagram.com/stelkmakassar/" target="_blank" rel="noopener">Instagram</a></li>
      <li><a href="https://m.facebook.com/stelkmakassar/" target="_blank" rel="noopener">Facebook</a></li>
      <li><a href="Stelkmks.ypt@gmail.com" target="_blank" rel="noopener">Email</a></li>
      <li><a href="https://www.youtube.com/channel/UCSuUu4RCSjMBiyJopVX-elQ" target="_blank" rel="noopener">Youtube</a></li>
    </ul>
    <h3>Our Website</h3>
    <ul>
      <li>Also visit our website to know more about SMK TELKOM MAKASSAR</li><br>
      <li><a href="https://smktelkom-mks.sch.id/" target="_blank" rel="noopener">SMK TELKOM MAKASSAR</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  margin: 40px 0 0;
  color: #2c3e50;
  font-weight: 600;
}
p{
  font-weight: 500;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  text-decoration: none;
  color: red;
  font-weight: 600;
}
a:hover{
  color: #ad2218;
}
</style>