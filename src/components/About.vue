<template>
    <section class="section-start">
        <h4>Nosotros</h4>
        <h2>Información sobre la compañía</h2>
        <p>Aprende más acerca de la empresa y el equipo detrás de ella</p>
    </section>
    <section class="section-center"> 
        <div>
            <img src="../assets/aboutimg.png" alt="">
        </div>
        <div>
            <p>Hemos ayudado a muchas compañías a lo largo de estos años</p>
            <h2>Esto solo es el comienzo </h2>
            <ul>
                <li>
                    <h2>400+</h2>
                    <p>Empresas</p>
                </li>
                <li>
                    <h2>600%</h2>
                    <p>Crecimiento en 2 años</p>
                </li>
                <li>
                    <h2>10k</h2>
                    <p>Préstamos otorgados</p>
                </li>
                <li>
                    <h2>200+</h2>
                    <p>Reseñas de 5 estrellas</p>
                </li>
            </ul>
        </div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style scoped>

.section-center p,
h4{
    color: #0088dF;
}

h2{
    font-size: 2.5em;
}

section{
    font-family: Arial, Helvetica, sans-serif;
}
.section-start{
    width: 100;
    text-align: center;
    margin-top: 50px;
}

.section-center{
    background: #f1f1f2;
    margin-top: 100px;
    padding: 100px 0 100px 0;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10%;
}

.section-center h2{
    margin-top: 10px;
    margin-bottom: 30px;
}

.section-center ul h2{
    margin-bottom: 10px;
} 

.section-center ul li{
    margin-top: 30px;
}

.section-center ul{
    padding-left: 0;
    display: flex;
    flex-flow:wrap;
    list-style: none;
    gap: 15%;
}

.section-center ul li{
    width: 30%;
}

.section-center ul li h2{
    font-size: 3.5em;
    color: #005b94;
}

.section-center ul li p{
    color: black;
}


    
</style>