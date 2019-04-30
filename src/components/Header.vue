<template>
  <header class="page__header">
    <div class="header__form">
      <h1>Find the perfect home for you.</h1>
      <form action="POST">
        <div class="form__row">
          <label for="location">Location:</label>
          <input type="text" name="location" id="location" class="form__input">
        </div>
        <div class="form__row">
          <div class="form__group">
            <label for="location">Location:</label>
            <input type="text" name="location" id="location" class="form__input"> 
          </div>
          <div class="form__group">
            <label for="location">Location:</label>
            <input type="text" name="location" id="location" class="form__input"> 
          </div>
        </div>
        <button type="submit" class="form__button ">SEARCH</button>
      </form>
    </div>
  </header>
</template>
<style>
.page__header {
  height: 600px;
  background: url("../assets/Background.png");
  text-align: center;
  display: flex;
  margin: auto;
}
.header__form {
  background: #ffffff;
  border-radius: 10px;
  padding: 2em;
  margin: auto;
}
</style>
