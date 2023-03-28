<template>
  <table>
  <tr>
  <td><label for="nama">Masukkan Nama Lengkap Anda</label></td>
  </tr>
  <tr><td><input type="text" placeholder="Masukkan Nama Anda" /></td></tr>
  </table>
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
label{
  font-weight: 600;
}

input{
  color: red;
  border-color: red;
  background: pink;
}

input::-webkit-input-placeholder{
  color: #ff79a1;
}
</style>