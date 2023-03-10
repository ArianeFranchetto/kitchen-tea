<template>
    <div class="container-lista">
    <div class="title-lista">
        <h2>
            Caso queira levar um presente<br> dê uma olhada na lista.

        </h2>
    </div>
<div class="flexbox-lista">
    <section class="lista">
        <div>
            <ul>
                <li>lista</li>
                <li>lista</li>
                <li>lista</li>
                <li>lista</li>
                <li>lista</li>
            </ul>
        </div>
    </section>

    <div>
        <img class="casa-img" src="../assets/img/casa.png">
    </div>
</div>

</div>
</template>

<script>
</script>

<style scoped>
* {
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

.container-lista {
    background-color: #645555;
    border-radius: 5px;
    text-align: center;
    height: 400px;
    width: 400px;
  
  
    
}

h2 {
    font-size: 1.4rem;
    margin-bottom: 2px;
}

ul {
    list-style: none;
}

.lista {
    background-color: #CA8158;
    width: 400px;
    height: 300px;
    border-radius: 5px;
    margin-left: 7px;
    margin-top: 15px;
    

}

.casa-img {
    width: 100px;
    margin-top: 14.5rem;
    margin-right: 7.0rem;
 
}

.flexbox-lista {
    display: flex;
    justify-content: center;
  
}
</style>