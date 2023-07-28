<template>
  <div>
    <Header/>
    <Notes :notes="notes"/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Notes from './components/Notes.vue';
  export default {
    components: {
      Header,
      Notes
    },
    data(){
      return {
        notes: [
          {
            id: 1,
            title: 'Vue',
            date: '07.03.2022',
            desc: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor'
          },
          {
            id: 2,
            title: 'React',
            date: '15.08.2000',
            desc: 'Lorem ipsum dolor sit amet'
          },
          {
            id: 3,
            title: 'Angular',
            date: '08.07.1981',
            desc: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor'
          },
        ],
      }
    }
  }
</script>

<style scoped>

</style>