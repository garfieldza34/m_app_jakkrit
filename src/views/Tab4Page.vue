<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 4</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 4</ion-title>
        </ion-toolbar>
      </ion-header>

<ion-content fullscreen>
        <ion-card>
          <img src="https://scontent.fphs2-1.fna.fbcdn.net/v/t1.6435-9/118098771_1682404401948515_1388789842709794893_n.jpg?_nc_cat=101&ccb=1-5&_nc_sid=09cbfe&_nc_eui2=AeFvb2VjvRUnnk4o0K-f7lfslHLw2pjnOliUcvDamOc6WOKVQW0pdYLbZ8xf_imm56RpXqWSkGL7Z8zDsIh18I1l&_nc_ohc=jdqVdqNQBG4AX8Opapo&_nc_ht=scontent.fphs2-1.fna&oh=00_AT8vOPzfgrex1eLC4nbNFIQCoin_-8PPLS63rcs73yJYmQ&oe=624BBCB1" />
          <ion-card-header>
            
            <ion-card-title>จักรกฤษ สุขาจารย์</ion-card-title>
          </ion-card-header>
          <ion-card-content>
            รหัสนักศึกษา : 62442206003-5
<ion-card-subtitle>เบอร์โทร : 0969121131</ion-card-subtitle>
           

          </ion-card-content>
        </ion-card>
      </ion-content>
      
      <ExploreContainer name="Tab 4 page" />
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default defineComponent({
  name: 'Tab4Page',
  components: {IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});


</script>
