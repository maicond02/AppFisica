<template>
    <div class="flex flex-wrap align-items-center justify-content-center">
        <Card style="min-width: 99vw; max-width: 99vw; min-height: 80vh;">
            <template #title>
                
            </template>
            <template #content>
                <div class="grid grid-nogutter">
                    <div class="col">
                        <div class="flex flex-wrap">
                                <div class="flex flex-column">
                                    <h2 class="flex align-items-center justify-content-center">Login</h2>
                                    <p for="Email">Usuário</p>
                                    <InputText style="min-width: 300px"/>
                                    <br>
                                    <p for="Senha">Senha</p>
                                    <InputText style="min-width: 300px"/>
                                    <br>
                                    <nuxt-link to="/home" class=" flex align-items-center justify-content-center">
                                        <Button class="p-button-outlined" label="Login" style="min-width: 150px" />
                                    </nuxt-link> 
                                </div>
                            </div>
                    </div>
                    <div class="col">
                        <h2 class="flex align-items-center justify-content-center ">FisicaFacil</h2>
                        <p class="flex align-items-center justify-content-center ">Aprenda do seu jeito, de qualquer lugar.</p>
                    </div>
                </div>
            </template>
        </Card>
    </div>
</template>

<script>

</script>

<style scoped>
    .p-card{
        background-color: rgba(0, 0, 0, 0.5);
    }
    .p-button{
        color: white !important;
    }
    a{
        text-decoration: none;
    }
</style>