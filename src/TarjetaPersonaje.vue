<template>
<div class="edicion">
  
    <img :src= 'imagen'/>
      <p>{{nombre}}</p>
</div>
</template>

<script>
export default {
     name: "TarjetaPersonaje",
     props: {
        nombre: String,
        imagen: String
} }
</script>

<style>

.edicion {
    display: flex;
    align-items: center;
    margin-left: 3rem;
    padding-top: 2rem;
}
p {
    color: green;
    font-weight: 700;
    font-size: 18px;
    margin-left: 2rem;
  
}

img {
    border-radius: 50%;
    width: 100px;
   

}
</style>

