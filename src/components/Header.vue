<template>
  <header>
    <div class="brand">
      <img src="../assets/document.svg" alt="avatar">
      <h5>Just Edit</h5>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style lang="scss" scoped>
header {
  display: flex;
  background-color: white;
  margin: 0;
  padding: 17px 5%;
  color: whitesmoke;
  box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.1);
  background: #fbf3f259;

  .brand {
    flex: 1;
    display: flex;
    align-items: center;

    img {
      height: 35px;
      border-radius: 50%;
      margin-right: 17px;
    }

    h5 {
      font-size: 18px;
      margin: 0;
      font-weight: normal;
      letter-spacing: 0.4px;
      color: #d8625e;
      opacity: 0.7;
      text-transform: capitalize;
    }
  }
}
</style>


