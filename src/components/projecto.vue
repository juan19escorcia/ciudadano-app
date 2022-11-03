<template>
    <div class="contenedor1">
        <div class="contenido">
                    <div class="correo">
                        <img src="imagen/correo-electronico.png" alt="">
                        <input type="email" placeholder="INGRESE SU CORREO">
                    </div>
                    <div class="contraseña">
                        <img src="candado.png" alt="">
                        <input type="password" placeholder="INGRESE SU CONTRASEÑA" name="password">
                        <button type="children" class="Ocultar"></button>
                    </div>
                    <div class="botones">
                        <transition name="fade" mode="out-in">
                            <button>INICIAR SESION</button> 
                        </transition>
                      
                         <a href="http://">REGISTRARSE</a>
                    </div>
        </div>
            <div class="foto">
                <div class="tre">
                    juan manuel
                </div>
            </div>
        </div>
  
</template>

<script>
export default {

}
</script>

<style>
 
   .Ocultar{
    width: 2rem;
    height: 2rem;
    margin: 3%;
   }
   .contenedor1{
    background-color: aqua;
    width: 80%;
    height: 50rem;
    align-items: center;
    padding: 1%;
    display: flex;
    justify-content: space-between;
    align-items: center;
   }
   .contenido{
    background-color: brown;
    width: 48%;
    height: 46rem;
    padding: 0;
    margin: 0;
    border: 2px solid rgb(255, 255, 255);
   }
   .correo{
    background-color: rgb(0, 0, 0);
    width: 97%;
    height: 8rem;
    padding: 1%;
    display: flex;
    border: 2px solid rgb(255, 255, 255);
   }
   input{
    width: 80%;
    height: 2rem;
    margin-top: 3%;
   }
   .contraseña{
    background-color: rgb(0, 37, 220);
    width: 97%;
    height: 8rem;
    padding: 1%;
    display: flex;
    border: 2px solid rgb(255, 255, 255);

   }
   .botones{
    background-color: rgb(0, 0, 0);
    width: 97%;
    height: 8rem;
    padding: 1%;
    border: 2px solid rgb(255, 255, 255);
    
   }
   button{
    width: 90%;
    height: 40%;
    display: flex;
    text-align: center;
 
   }
   :hover a{
    color:aliceblue;
   
   }
   a{
    color:blue
   }
   .foto{
    background-color: rgb(0, 235, 4);
    width: 48%;
    height: 46rem;
    padding: 0;
    margin: 0;
    border: 1px solid black;
   }
   img{
    width: 4rem;
    height: 4rem;

   }


</style>