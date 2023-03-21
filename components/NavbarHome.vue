<template>
    <div>
        <Menubar :model="items" class="menubar-home flex align-items-center justify-content-center">
            <template #start>

            </template>
            <template #end>
                <Button label="Registrar-se" class="p-button-raised p-button-help p-button-text" icon="pi pi-fw pi-user-plus"/>
                <Button label="Já sou aluno" icon="pi pi-fw pi-user" class="p-button-outlined p-button-help"/>
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
    .p-menubar::v-deep{
        background-color: rgba(0, 0, 0, 0.5);
        color: white;
    }
   .p-menuitem-text{
        color: white !important;
    }
    .p-button{
        color: white !important;
    }
</style>
