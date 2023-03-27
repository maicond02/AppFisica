<template>
    <div class="div-container flex flex-wrap align-items-center justify-content-center">
        <Card style="min-width: 98.3vw; max-width: 98.3vw;" class="card-container">
            <template #content>
                <div class="grid grid-nogutter flex align-items-start justify-content-center">
                    <Card style="min-width: 400px;max-width: 400px;min-height: 600px; max-height: 600px;">
                        <template #content>
                                <div class="col flex align-items-start justify-content-center">
                                    <div class="flex flex-wrap">
                                            <div class="flex flex-column">
                                                <h2 class="flex align-items-center justify-content-center" style="color:black;">Login</h2>
                                                <p for="Email" style="color:black;">Usuário</p>
                                                <InputText style="min-width: 300px"/>
                                                <br>
                                                <p for="Senha" style="color:black;">Senha</p>
                                                <InputText style="min-width: 300px"/>
                                                <br>
                                                <nuxt-link to="/home" class=" flex align-items-center justify-content-center">
                                                    <Button class="p-button-outlined" label="Login" style="min-width: 150px;" />
                                                </nuxt-link> 
                                                <br>
                                                <nuxt-link to="/home" class=" flex align-items-center justify-content-center">
                                                    <button class="cta">
                                                        <span>Registrar-se</span>
                                                        <svg viewBox="0 0 13 10" height="10px" width="15px">
                                                            <path d="M1,5 L11,5"></path>
                                                            <polyline points="8 1 12 5 8 9"></polyline>
                                                        </svg>
                                                    </button>
                                                </nuxt-link> 
                                            </div>
                                        </div>
                                </div>      
                        </template>
                    </Card>
                    <Card class="card-two" style="min-width: 400px;max-width: 400px;max-height: 600px;min-height: 600px;">
                        <template #content>
                            <div class="col flex align-items-center justify-content-start">
                                    <div class="flex flex-wrap ">
                                        <div class="flex flex-column">
                                            <h2 class="flex align-items-center justify-content-center " style="color:white;">FísicaFácil</h2>
                                            <p class="flex align-items-center justify-content-center " style="color:white;">Aprenda do seu jeito, de qualquer lugar.</p>
                                            <br>
                                            <br>
                                            <div class="flex align-items-center justify-content-center">
                                                <div class="planet">
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                        </template>
                    </Card>
                </div>
            </template>
        </Card>
    </div>
</template>

<script>

</script>

<style scoped>
   .card-container{
        background-color: #ffffff80;
    }
    .p-button{
        color: black !important;
    }
    a{
        text-decoration: none;
    }
    img{
        height: 60vh;
    }
    .card-two{
        background-color: rgba(0, 0, 0, 0.836);
    }

    .cta {
 position: relative;
 margin: auto;
 padding: 12px 18px;
 transition: all 0.2s ease;
 border: none;
 background: none;
 cursor: pointer;
}

.cta:before {
 content: "";
 position: absolute;
 top: 0;
 left: 0;
 display: block;
 border-radius: 50px;
 background: #b1dae7;
 width: 45px;
 height: 45px;
 transition: all 0.3s ease;
}

.cta span {
 position: relative;
 font-family: "Ubuntu", sans-serif;
 font-size: 18px;
 font-weight: 700;
 letter-spacing: 0.05em;
 color: #234567;
}

.cta svg {
 position: relative;
 top: 0;
 margin-left: 10px;
 fill: none;
 stroke-linecap: round;
 stroke-linejoin: round;
 stroke: #234567;
 stroke-width: 2;
 transform: translateX(-5px);
 transition: all 0.3s ease;
}

.cta:hover:before {
 width: 100%;
 background: #b1dae7;
}

.cta:hover svg {
 transform: translateX(0);
}

.cta:active {
 transform: scale(0.95);
}

    .planet {
  display: block;
  width: 125px;
  height: 125px;
  position: relative;
  transform-style: preserve-3d;
  border-radius: 50%;
  background: #fcc96b;
  background: #fcc96b;
  background: linear-gradient(
    180deg,
    #fcc96b 0%,
    #fcc96b 15%,
    #f7ae01 15%,
    #f7ae01 19%,
    #fcc96b 19%,
    #fcc96b 22%,
    #f7ae01 22%,
    #f7ae01 28%,
    #fcc96b 28%,
    #fcc96b 31%,
    #fcc96b 33%,
    #fcc96b 36%,
    #f7ae01 36%,
    #f7ae01 48%,
    #fcc96b 48%,
    #fcc96b 55%,
    #f7ae01 55%,
    #f7ae01 66%,
    #fcc96b 66%,
    #fcc96b 70%,
    #f7ae01 70%,
    #f7ae01 73%,
    #fcc96b 73%,
    #fcc96b 82%,
    #f7ae01 82%,
    #c7ba9d 86%,
    #fcc96b 86%
  );
  box-shadow: inset 0 0 25px rgba(0, 0, 0, 0.25),
    inset 8px -4px 6px rgba(199, 128, 0, 0.5),
    inset -8px 4px 8px rgba(255, 235, 199, 0.5), inset 20px -5px 12px #f7ae01,
    0 0 100px #ffffff59;
  transform: rotateZ(-15deg);
}

.planet::before {
  position: absolute;
  content: "";
  display: block;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  border: 16px solid #e1a519;
  border-top-width: 0;
  border-radius: 50%;
  box-shadow: 0 -2px 0 #c18620;
  animation: rings1 0.8s infinite linear;
}

.planet::after {
  position: absolute;
  content: "";
  display: block;
  width: 100%;
  height: 100%;
  box-sizing: border-box;
  border: 8px solid #d48b0c;
  border-top-width: 0;
  border-radius: 50%;
  box-shadow: 0 -2px 0 #b99309;
  animation: rings2 0.8s infinite linear;
}

@keyframes rings1 {
  0% {
    transform: rotateX(65deg) rotateZ(0deg) scale(1.75);
  }

  100% {
    transform: rotateX(65deg) rotateZ(360deg) scale(1.75);
  }
}

@keyframes rings2 {
  0% {
    transform: rotateX(65deg) rotateZ(0deg) scale(1.7);
  }

  100% {
    transform: rotateX(65deg) rotateZ(360deg) scale(1.7);
  }
}
</style>