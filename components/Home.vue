<template>
    <div class="flex flex-wrap align-items-center justify-content-center">
        <div class="grid grid-nogutter">
            <div class="col">
                <Card style="min-width: 98vw;">
                    <template #title>

                    </template>
                    <template #content>
                        <div class="flex align-items-start justify-content-center">
                            <div>
                                <div class="flex-column flex-wrap flex align-items-center justify-content-center">
                                    <div>
                                        <h2 style="color:black;">Aprenda física de maneira totalmente gratuíta e descomplicada.</h2>
                                    </div>
                                    <div>
                                        <p style="color:black;">O mapa completo para você impulsionar seus estudos.</p>
                                    </div>
                                    <div>
                                        <Button label="Registrar-se gratuitamente" icon="pi pi-user-plus" class="p-button-outlined p-button-help"/>
                                    </div>
                                    <br>
                                    <div>
                                        <img src="../static/images/Team building _Monochromatic.png" alt="">
                                    </div>
                                </div>
                            </div>
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
        background-color: white;
    }
    .p-button{
        color: black !important;
    }
    .card-chield{
        background-color: white;
    }
    img{
        height: 60vh;
    }
</style>