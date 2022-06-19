<template>
  <ion-page />
</template>

<script>
//const router = useIonRouter()
export default {
  async mounted(){
    await useIonRouter.push("/home")
    }
};
</script>

<style></style>
