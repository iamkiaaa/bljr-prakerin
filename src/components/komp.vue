<template>
  <h3>Kotak Pertanyaan</h3>
  <form action="">
  <input type="text" placeholder="Nama Lengkap" /><br>
  <input type="text" placeholder="No Telepon"><br>
  <input type="text" placeholder="Alamat Email"><br>
  <input type="text" placeholder="Subjek"><br>
  <textarea rows="4" cols="30" placeholder="Pertanyaan"></textarea>
  </form>
</template>

<script>
export default {
  name: 'newComp',
  props: {
    paraf: String,
  },
};
</script>

<style>
input, textarea{
  border: none;
  border-radius: 5px;
  background: #D3D3D3;
  padding: 10px;
  margin: 10px;
  color: #808080;
  width: 350px
}

input::-webkit-input-placeholder{
  color: #808080;
}
</style>