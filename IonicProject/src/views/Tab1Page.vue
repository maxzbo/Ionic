<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tim</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tim</ion-title>
        </ion-toolbar>
      </ion-header>
      <ExploreContainer name="Tim" />
      <center>
      <ion-button>Default</ion-button>
      <ion-button :disabled="true">Disabled</ion-button>
      </center>
    </ion-content>
  </ion-page>
</template>
<script lang="ts">
  import { IonButton } from '@ionic/vue';
  import { defineComponent } from 'vue';

  export default defineComponent({
    components: { IonButton },
  });
  
</script>



<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
</script>
