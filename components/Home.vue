<template>
    <div class="flex flex-wrap align-items-center justify-content-center">
        <Card style="min-width: 95%; max-width: 95%; min-height: 80vh;">
            <template #title>
                <div class="flex-column flex-wrap flex align-items-center justify-content-center">
                    <div style="max-width: 60%;">
                        <h2>Aprenda física de maneira totalmente gratuíta e descomplicada.</h2>
                    </div>
                    <div>
                        <p>O mapa completo para você impulsionar seus estudos.</p>
                    </div>
                    <div>
                        <Button label="Registrar-se gratuitamente" icon="pi pi-user-plus" class="p-button-raised p-button-help p-button-text"/>
                    </div>
                    <br>
                    <div>
                        <iframe  style="min-width: 50vw; min-height: 50vh;" src="https://www.youtube.com/watch?v=XLILd0R8btg&ab_channel=Rocketseat">
                        </iframe >
                    </div>
                </div>
            </template>
            <template #content>
                <div>
                    
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