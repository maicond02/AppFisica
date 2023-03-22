<template>
    <div class="flex flex-wrap align-items-center justify-content-center">
        <Card style="min-width: 99%; max-width: 99%; min-height: 80vh;">
            <template #title>

            </template>
            <template #content>
                <div class="grid">
                    <div class="col">
                        <nuxt-link to="">
                            <Card>
                                <template #content>
                                    <div class="flex flex-wrap align-items-center justify-content-center">
                                        <h2>Aulas</h2>
                                    </div>
                                </template>
                            </Card>
                        </nuxt-link>
                    </div>
                    <div class="col">
                        <nuxt-link to="">
                            <Card>
                                <template #content>
                                    <div class="flex flex-wrap align-items-center justify-content-center">
                                        <h2>Materiais</h2>
                                    </div>
                                </template>
                            </Card>
                        </nuxt-link>
                    </div>
                </div>
                <div class="grid">
                    <div class="col">
                        <nuxt-link to="">
                            <Card>
                                <template #content>
                                    <div class="flex flex-wrap align-items-center justify-content-center">
                                        <h2>Ao vivo</h2>
                                    </div>
                                </template>
                            </Card>
                        </nuxt-link>
                    </div>
                    <div class="col">
                        <nuxt-link to="">
                            <Card>
                                <template #content>
                                    <div class="flex flex-wrap align-items-center justify-content-center">
                                        <h2>Fórum</h2>
                                    </div>
                                </template>
                            </Card>
                        </nuxt-link>
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
        text-decoration: none !important;
    }
</style>