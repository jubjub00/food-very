<template>
  <div class="card-master">
    <div class="card-main">
      <div class="card-star">
        <img src="../assets/heart.svg" alt="" style="width: 70%" />
      </div>
    </div>
    <div class="card-body">
      <h2 style="margin: 10px 20px">กรหมี่ไก่</h2>
      <div class="card-desc">
        <div class="desc">
          <img src="../assets/star.svg" alt="" width="24" />
          4.9
        </div>
        <div class="desc">
          <img src="../assets/clock.svg" alt="" width="24" />
          4.9
        </div>
        <div class="desc">
          <img src="../assets/location.svg" alt="" width="24" />
          4.9
        </div>
      </div>
      <div class="card-foot">
        <div>ก๋วยเตี๋ยว</div>
        <div>ก๋วยเตี๋ยว</div>
        <div>ก๋วยเตี๋ยว</div>
        <div>ก๋วยเตี๋ยว</div>
        <div>ก๋วยเตี๋ยว</div>
        <div>ก๋วยเตี๋ยว</div>
        <div>ก๋วยเตี๋ยว</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "cardMain",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.card-foot {
    margin-top: 20px;
    position: relative;
    display: flex;
    max-width: -webkit-fill-available;
    overflow-x: scroll;
}

.card-foot > div {
  margin-left: 20px;
  padding: 0 10px;
  height: 35px;

  background: #28b7ff;
  border-radius: 7px;
}
.desc {
  display: flex;
  color: #28b7ff;
  align-items: center;
}
.desc > img {
  margin-left: 20px;
  margin-right: 10px;
}
.desc-foot {
  background: #28b7ff;
  border-radius: 7px;
}
.card-main {
  background-image: url("../assets/food.jpeg");
  border-radius: 30px;
  background-repeat: no-repeat;
  background-size: cover;
  height: 150px;
  position: relative;
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}

h2 {
  color: #28b7ff;
}

.card-desc {
  display: flex;
}

.card-body {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.card-master {
  background: white;
  padding-bottom: 50px;
  border-radius: 30px;
  position: relative;
}

.card-type {
  position: absolute;
  left: 10px;
  top: 10px;
  padding: 5px 10px;
  border-radius: 30px;
  background: skyblue;
}

.card-star {
  position: absolute;
  top: 10px;
  right: 10px;
  border-radius: 100%;
  background: white;
  width: 24px;
  height: 24px;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
