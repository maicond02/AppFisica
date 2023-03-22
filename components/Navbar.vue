<template>
    <Menubar :model="items" orientation="vertical"/>
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
                     label:'Aulas',
                  },
                  {
                     label:'Materiais',
                  },
                  {
                     label:'Fórum',
                  },
                  {
                     label:'Aulas ao vivo',
                  },
                  {
                     label:'Usuário',
                     icon:'pi pi-fw pi-user',
                     items:[
                        {
                           label:'Perfil',
                           icon:'pi pi-fw pi-user-plus',
  
                        },
                        {
                           label:'Sair',
                           icon:'pi pi-fw pi-user-minus',
  
                        },
                     ]
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
    ::v-deep .p-submenu-list{
      background-color: rgba(0, 0, 0, 0.5) !important;
    }
</style>
  