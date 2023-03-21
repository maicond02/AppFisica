<template>
    <div class="flex flex-wrap align-items-center justify-content-center">
        <Card style="min-width: 95%; max-width: 95%; min-height: 80vh;">
            <template #title>
                <p class="flex align-items-end justify-content-center ">Registrar-se</p>
            </template>
            <template #content>
                <div class="flex-column flex-wrap flex align-items-center justify-content-center">
                    <div>
                        <div class="flex flex-wrap">
                        <div class="flex align-items-center justify-content-center ">
                            <div class="flex flex-column">
                                <p for="Email">Usuário</p>
                                <InputText style="min-width: 300px"/>
                                <br>
                                <p for="Email">Email</p>
                                <InputText style="min-width: 300px"/>
                                <br>
                                <p for="Senha">Senha</p>
                                <InputText/>
                                <br>
                                <Button class="p-button-outlined" label="Registrar-se" />

                            </div>
                        </div>
                    </div> 
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
</style>