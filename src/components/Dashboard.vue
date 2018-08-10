<template>
  <div id="appBoard">
    <div class="row">
      <div class="box">
        Box 1
      </div>
      <div class="box">
        Box 2
      </div>
    </div>
    <div class="row">
      <div class="box">
        Box 1
      </div>
      <div class="box">
        Box 2
      </div>
    </div>
    
  </div>
</template>
<style>
#appBoard {
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 27.6rem;
  background: white;
}
.row {
  display: flex;
  flex-direction: row;
  align-items: stretch;
  width: 100%;
  height: 100%;
}
.box {
  border: 2px solid black;
  flex-grow: 1;
  margin: 5px;
  text-align: center;
}
</style>






