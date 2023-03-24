<template>
    <div>
        <Menubar :model="items" class="menubar-home flex align-items-center justify-content-center">
            <template #start>

            </template>
            <template #end>
                <nuxt-link to="/register">
                    <Button label="Registrar-se" class="p-button-raised p-button-secondary p-button-text" icon="pi pi-fw pi-user-plus"/>
                </nuxt-link>
                <nuxt-link to="/login">
                    <Button label="Já sou aluno" icon="pi pi-fw pi-user" class="p-button-outlined p-button-secondary"/>
                </nuxt-link>
            </template>
        </Menubar>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                items: [
                    {
                    label:'Home',
                    to:'/'
                    },
                    {
                    label:'Programas',
                    },
                    {
                    label:'Sobre',
                    },
                    {
                    label:'Para empresas',
                    },
                ]       
            }
        }
    }
</script>

<style scoped>
    ::v-deep .p-menubar{
        background: white;
        color: black;
    }
    ::v-deep .p-menuitem-text{
        color: black !important;
    }
    .p-button{
        color: black !important;
    }
    a{
        text-decoration: none !important;
    }
</style>
