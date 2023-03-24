<template>
    <div class="div-container flex flex-wrap align-items-center justify-content-center">
        <Card style="min-width: 99vw; max-width: 99vw;" class="card-container">
            <template #content>
                <div class="grid grid-nogutter flex align-items-start justify-content-center">
                    <Card class="card-chield" style="min-width: 400px;max-width: 400px;min-height: 600px; max-height: 600px;">
                        <template #content>
                                <div class="col flex align-items-start justify-content-center">
                                    <div class="flex flex-wrap">
                                            <div class="flex flex-column">
                                                <h2 class="flex align-items-center justify-content-center" style="color:black;">Registrar-se</h2>
                                                <p for="Email" style="color:black;">Email</p>
                                                <InputText style="min-width: 300px"/>
                                                <br>
                                                <p for="Email" style="color:black;">Usuário</p>
                                                <InputText style="min-width: 300px"/>
                                                <br>
                                                <p for="Senha" style="color:black;">Senha</p>
                                                <InputText style="min-width: 300px"/>
                                                <br>
                                                <nuxt-link to="/home" class=" flex align-items-center justify-content-center">
                                                    <Button class="p-button-outlined" label="Registrar" style="min-width: 150px;" />
                                                </nuxt-link> 
                                            </div>
                                        </div>
                                </div>      
                        </template>
                    </Card>
                    <Card style="min-width: 400px;max-width: 400px;max-height: 600px;" class="card-two">
                        <template #content>
                            <div class="col flex align-items-center justify-content-start">
                                    <div class="flex flex-wrap">
                                        <div class="flex flex-column">
                                            <h2 class="flex align-items-center justify-content-center " style="color:white;">FisicaFacil</h2>
                                            <p class="flex align-items-center justify-content-center " style="color:white;">Aprenda do seu jeito, de qualquer lugar.</p>
                                            <img class="flex align-items-center justify-content-center " src="../static/images/girl_laptop.png" alt="">
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
    background-color: white;
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
</style>