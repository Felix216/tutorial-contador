<template>
  <div>
    <MostrarMensajeComponent/>
    <ListaItemComponent/>
    <BotonMostrarComponent/>
    <BotonDeshabilitadoComponent/>
    <ContadorComponent/>
    <CambiarMensajeComponent/>
    <ComponentePadre/>
  </div>
</template>

<script>
import MostrarMensajeComponent from '../components/MostrarMensajeComponent.vue'
import ListaItemComponent from '../components/ListaItemsComponent.vue'
import BotonMostrarComponent from '../components/BotonMostrarComponent.vue'
import BotonDeshabilitadoComponent from '../components/BotonDeshabilitadoComponent.vue'
import ContadorComponent from '../components/ContadorComponent.vue'
import CambiarMensajeComponent from '../components/CambiarMensajeComponent.vue'
import ComponentePadre from '../components/ComponentePadre.vue'

export default {
  name: 'HomeView',
  components: {
    MostrarMensajeComponent,
    ListaItemComponent,
    BotonMostrarComponent,
    BotonDeshabilitadoComponent,
    ContadorComponent,
    CambiarMensajeComponent,
    ComponentePadre
  }
}
</script>
