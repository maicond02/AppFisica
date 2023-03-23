<template>
    <div class="flex flex-wrap align-items-center justify-content-center">
        <div class="grid grid-nogutter">
            <div class="col">
                <Card style="min-width: 98vw;">
                    <template #title>
                        <div class="flex-column flex-wrap flex align-items-center justify-content-center">
                            <div style="max-width: 60%;" >
                                <h2 >Aprenda física de maneira totalmente</h2>
                                <h2 class="flex align-items-center justify-content-center">gratuíta e descomplicada.</h2>
                            </div>
                            <div>
                                <p>O mapa completo para você impulsionar seus estudos.</p>
                            </div>
                            <div>
                                <Button label="Registrar-se gratuitamente" icon="pi pi-user-plus" class="p-button-outlined p-button-help"/>
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
        </div>


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