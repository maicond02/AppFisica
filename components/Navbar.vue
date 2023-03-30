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
      background-color: rgba(255, 255, 255, 0.089);
    }
    ::v-deep .p-menuitem-text{
        color: white !important;
    }
    ::v-deep .p-submenu-icon{
      color: white !important;
    }

    ::v-deep .p-menuitem-icon{
      color: white !important;
   }
   ::v-deep .p-submenu-list{
      background-color: rgba(255, 255, 255, 0.089);
   }
   
</style>
  