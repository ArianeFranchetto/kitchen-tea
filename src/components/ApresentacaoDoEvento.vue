<template>
    <div class="container-maior">
    <div class="container">
         
            <h1>CHÁ DE CASA DA NANI</h1>
           <ul class="infos">
            <li>Local:</li>
            <li>Data:</li>
            <li>Horario:</li>
           </ul>

    </div>
</div>
</template>

<script>
</script>

<style scoped>
* {
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
   
}

.container-maior{
    display: flex;
    flex-direction: column;
    justify-content: center;
margin-top: 1px;
}
.container {
    background-color: #f0e5ac;
    display: flex;
    flex-direction: column;
     align-items: center;
    border-radius: 5px;
    width: 400px;
  

}



.infos {
    display: flex;
    flex-direction: column;
   list-style: none;
   font-size: 1.7rem;
   margin-top: 0.3rem;


}

</style>



