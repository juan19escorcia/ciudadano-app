<template>
    <div class="contenedor1">
        <form class="contenido">
            <h1>LOGIN</h1>
                    <div class="correo">
                       <video 
                        autoplay loop muted
                        poster="poster.png">
                        <source src="../assets/imagen/returning-visitor-3937930-3264519.mp4" type="video/mp4">
                        </video>
                        <input type="email" placeholder="INGRESE SU CORREO">
                    </div>
                    <div class="contraseña">
                        <video 
                        autoplay loop muted
                        poster="poster.png">
                        <source src="../assets/imagen/mobile-accounting-5161243-4328680.mp4" type="video/mp4">
                        </video>
                        <input type="password" placeholder="INGRESE SU CONTRASEÑA" name="password">
                        <button type="children" class="Ocultar"></button>
                    </div>
                    <div class="botones">
                        <input type="submit" value="INICIAR SESION">
                         <a href="http://">REGISTRARSE</a>
                    </div>
        </form>
            <div class="foto">
                <div class="tre">
                   
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
    height: 40rem;
    align-items: center;
    padding: 1%;
    display: flex;
    justify-content: space-between;
    align-items: center;
   }
   .contenido{
    background-color: rgb(255, 255, 255);
    width: 48%;
    height: 30rem;
    padding: 0;
    margin: 0;
    border: 2px solid rgb(255, 255, 255);
   }
   .correo{
    background-color: rgb(255, 255, 255);
    width: 97%;
    height: 4rem;
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
    background-color: rgb(255, 255, 255);
    width: 97%;
    height: 8rem;
    padding: 1%;
    display: flex;
    border: 2px solid rgb(255, 255, 255);

   }
   .botones{
    background-color: rgb(255, 255, 255);
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
    color:rgb(34, 110, 176);
   
   }
   a{
    color:blue
   }
   .foto{
    background-color: rgb(255, 255, 255);
    width: 48%;
    height: 30rem;
    padding: 0;
    margin: 0;
    border: 1px solid black;
   }
   video{
    width: 4rem;
    height: 4rem;
    background-color: aliceblue;
    border-radius: 50%;

   }


</style>