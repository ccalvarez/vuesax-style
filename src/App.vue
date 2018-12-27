<template>
  <vs-list>
    <vs-list-header title="Group 1"></vs-list-header>
    <vs-list-item title="Snickerdoodle" subtitle="An excellent companion"></vs-list-item>
    <vs-list-item title="Sapporo Haru" subtitle="An excellent polish restaurant, quick delivery and hearty, filling meals"></vs-list-item>
    <vs-list-header title="Group 2" color="success"></vs-list-header>
    <vs-list-item title="Enid's" subtitle="At night a bar, during the day a delicious brunch spot."></vs-list-item>
    <vs-list-item title="Veronika Ossi" subtitle="Has not watched anything recently"></vs-list-item>
  </vs-list>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import axios from 'axios';
import 'vuesax/dist/vuesax.css'; //Vuesax styles

export default {
  name: 'app',
  components: {
    HelloWorld,
  },
  data() {
    return {
      tareas: null,
    };
  },
  // mounted() {
  //   axios
  //     .get(process.env.VUE_APP_APIURL + '/users/5c1591a080980742861d7ef6/tasks')
  //     .then(response => {
  //       if (response.status === 200) {
  //         this.tareas = response.data;
  //       } else if (response.status === 204) {
  //       }
  //     })
  //     .catch(error => {});
  // },
};
</script>

<style>
</style>
