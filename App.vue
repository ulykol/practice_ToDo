<script>

</script>

<template>
   <header class= "header">
      <br>
        <div class="top__text">ToDo-list</div>
        <div class="undertoptext">You can do it</div>
      <br>
    </header>
    <div class="input">
    <input type="text" class="ToDO__text" id="taskInput" placeholder="Enter your task">
  </div>
    <button onclick="addTask()" class="Add__button">Add</button>
<div class="container">
  
  <div class="column" id="todo-column">
    
<h2>TO DO</h2>
  </div>
  <div class="column" id="progress-column">
    <h2>In Progress</h2>
  </div>
  <div class="column" id="done-column">
    <h2>Done</h2>
  </div>
</div>
</template>

<style>
</style>
