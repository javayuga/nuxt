<template>
  <div class="container">
    <h1>Baby Name Generator</h1>
    <p>Choose options and click on the "Find Names" button below</p>  

    <div class="options-container">
      <div class="option-container">
        <h4>1. Choose a gender</h4>
        <div class="option-buttons">
          <button class="option option-left">Boy</button>
          <button class="option">Unisex</button>
          <button class="option option-right">Girl</button>
        </div>
      </div>
      <div class="option-container">
        <h4>2. Choose the name's popularity</h4>
        <div class="option-buttons">
          <button class="option option-left">Trendy</button>
          <button class="option option-right">Unique</button>
        </div>
      </div>
      <div class="option-container">
        <h4>3. Choose the name's length</h4>
        <div class="option-buttons">
          <button class="option option-left">Short</button>
          <button class="option">All</button>
          <button class="option option-right">Long</button>
        </div>
      </div>
    </div>  
  </div>
</template>

<style scoped>
  .container {
    font-family: Arial, Helvetica, sans-serif;
    color:rgb(27, 6, 138);
    max-width: 50rem;
    text-align: center;
    margin: 0 auto;
  }

  .h1{
    font-size: 3rem;
  }

  .options-container {
    background-color: rgb(255, 238, 236);
    border-radius: 2rem;
    padding: 1rem;
    margin: 0 auto;
    width: 95%;
    margin-top: 4rem;
  }

  .option-container {
    margin-bottom: 2rem;
  }

  .option{
    background: white;
    outline: 0.15rem solid rgb(249, 87, 89);
    border:none;
    padding: 0.75rem;
    width: 12rem;
    font-size: 1rem;
    color: rgb(27, 6, 138);
    cursor: pointer;
    font-weight: 200;
  }
  .option-right{
    border-radius: 0 1rem 1rem 0;
  }
  .option-left{
    border-radius: 1rem 0 0 1rem;
  }
</style>