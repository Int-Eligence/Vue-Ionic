<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Memories</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <ion-list>
        <ion-item router-link="/memory/1">Soumya</ion-item>
        <ion-item router-link="/memory/2">Soham</ion-item>
        <ion-item router-link="/memory/3">Sumit</ion-item>
        <ion-item router-link="/memory/4">Ranik</ion-item>
        <ion-item router-link="/memory/5">Sujoy</ion-item>
      </ion-list>
    </ion-content>
  </ion-page>
</template>

<script>
import {
  IonPage,
  IonHeader,
  IonTitle,
  IonContent,
  IonToolbar,
  IonList,
  IonItem,
} from "@ionic/vue";
export default {
  components: {
    IonPage,
    IonHeader,
    IonTitle,
    IonContent,
    IonToolbar,
    IonList,
    IonItem,
  },
};
</script>
