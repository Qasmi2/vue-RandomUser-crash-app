## Vue@3.0.5

    This repository has basic vue app 

## File

    three file

    - app.js
    - index.html
    - style.css

## index.html

    include script 
    1. (<script src="https://unpkg.com/vue@3.0.5"></script>)
    2. (<script src="app.js"></script>)

    inside `#app` div

      <div id="app">
        <img v-bind:class="gender" v-bind:src="picture" :alt="`${firstname} ${lastname}`" />
        <h1>Hello {{firstname}} {{lastname}}</h1>
        <h3>Email:{{email}}</h3>
        <button v-on:click="getUser()"  v-bind:class="gender">Get Random User</button>

      </div>

## app.js

    vue.createApp have date() and methods:
    methods: getUser() 

## style.css 

    css


    