<template>
    <ion-page>
        <ion-header :translucent="true">
            <ion-toolbar>
                <ion-title>Blank</ion-title>
            </ion-toolbar>
        </ion-header>

        <ion-content :fullscreen="true">
            <ion-header collapse="condense">
                <ion-toolbar>
                    <ion-title size="large">Blank</ion-title>
                </ion-toolbar>
            </ion-header>

            <div id="container">
                <iframe
                    width="560"
                    height="315"
                    src="https://www.youtube.com/embed/-5lobdvz4k4?si=HxeihGJb-sYvHx3e"
                    title="YouTube video player"
                    frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                    referrerpolicy="strict-origin-when-cross-origin"
                    allowfullscreen
                ></iframe>
            </div>
        </ion-content>
    </ion-page>
</template>

<script setup lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue'
</script>

<style scoped>
#container {
    text-align: center;

    position: absolute;
    left: 0;
    right: 0;
    top: 50%;
    transform: translateY(-50%);
}

#container strong {
    font-size: 20px;
    line-height: 26px;
}

#container p {
    font-size: 16px;
    line-height: 22px;

    color: #8c8c8c;

    margin: 0;
}

#container a {
    text-decoration: none;
}
</style>
