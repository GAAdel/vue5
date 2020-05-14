<template>
  <div id="app">
    <notes></notes>
  </div>
</template>

<script>
import MyNotes from './components/notes.vue';

export default {
  name: 'App',
  components: {
    notes: MyNotes,
  }
}
</script>
<style>
#app {
    margin: 50px 15px 15px 50px;
    background-color: rgb(226, 179, 162);

}

div label {
    float: left;
    width: 15%;
}

.knopka {
    margin: 15px 15px 15px 0px;
    width: 27%;
    border: 17px;
    padding: 5px 10px;
    border: 2px solid;
}

.book {
    border:1px solid;
    background-color: bisque;
}

#button-change {
    background-color: green;
    margin: 10px 10px 10px 0px;
    width: 10%;
    border: 10px;
    padding: 5px 10px;
    border: 0.4px solid;
}

#button-delete {
    background-color: red;
    margin: 10px 10px 10px 0px;
    width: 10%;
    border: 10px;
    padding: 5px 10px;
    border: 0.4px solid;
}

</style>
