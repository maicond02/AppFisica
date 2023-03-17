<template>
    <div>
        <Menubar :model="items" class="menubar-home flex align-items-center justify-content-center">
            <template #start>

            </template>
            <template #end>
                <Button label="Registrar-se" class="p-button-outlined" icon="pi pi-fw pi-user-plus"/>
                <Button label="Já sou aluno" icon="pi pi-fw pi-user"/>
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
                    label:'Início',
                    },
                    {
                    label:'Sobre nós',
                    },
                    {
                    label:'Doações',
                    },
                ]       
            }
        }
    }
</script>

<style scoped>
    .p-menubar::v-deep{
        background-color: #121214;
        color: white;
        border-bottom: 1px #8dd0ff solid;
    }
   .p-menuitem-text{
        color: white !important;
    }
</style>
