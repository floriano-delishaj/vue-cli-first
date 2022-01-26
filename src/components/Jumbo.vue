<template>
    
    <div class="jumbotron d-flex align-items-center">
        <div class="mx-5 jumbo-content">
            <h2>
                Un'avventura cooperativa selvaggia ti attende
            </h2>

            <div v-if="modal" class="btn btn-success mt-2">
                Per info
            </div>

            <p class="pt-3">
                Trova un amico e partite insieme per l'avventura più folle delle vostre vite in It Takes Two, un gioco d'avventura cooperativa a piattaforme che stravolge il suo genere.
            </p>

            <div class="btn btn-warning mt-2">
                Acquista ora!
            </div>

        </div>
    </div>

</template>



<script>

</script>


<style>

.jumbotron {
    background: url(../assets/img-1.jpg);
    height: 700px;
}

.jumbo-content {
    width: 20%;
    text-align: left;
    color: #fff
}


</style>