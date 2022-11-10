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
                        <input type="password" placeholder="INGRESE SU CONTRASEÑA" name="password"><br>
                    </div>
                    <input type="checkbox">
                    <label for="checkbox">Mostrar contraseña</label> <br>
                    <input type="submit" value="INICIAR SESION"> <br>
                    <a href="http://">REGISTRARSE</a>

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
    align-items: center;
    justify-content: center;
    border: 2px solid green;
   }
   .correo input, .contraseña input{
    width: 80%;
    height: 2rem;
    border: none;
   }
   .contraseña{
    background-color: rgb(255, 255, 255);
    width: 97%;
    height: 4rem;
    padding: 1%;
    display: flex;
    align-items: center;
    justify-content: center;
    border: 2px solid blue;

   }
   .botones{
    background-color: rgb(255, 255, 255);
    width: 97%;
    height: 8rem;
    padding: 1%;
    border: 2px solid red;
    
   }
    input[type="submit"]{
    width: 45%;
    height: 3rem;
    text-align: center;
 
   }
   .foto{
    background-color: rgb(255, 255, 255);
    width: 48%;
    height: 30rem;
    padding: 0;
    margin: 0;
   }
   a{
    color:rgb(5, 255, 51);
    padding: 5px;
   }

   video{
    width: 4rem;
    height: 4rem;
    background-color: aliceblue;
    border-radius: 50%;
    border: 1px solid black;
   }


</style>