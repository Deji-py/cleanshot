<template>
  <section class="newsletter">
    <div class="content">
      <div class="title -animation">Be the first to know</div>
      <p class="description -animation">
        We'll inform you about new apps and deals, but no spam, we promise.
      </p>
      <form class="form -animation">
        <input
          class="text-input"
          value=""
          type="email"
          placeholder="Your e-mail address"
          data-v-ae3811a1=""
        /><button class="action-button -standard -primary" data-v-6277d510="">
          <!----><span class="label" data-v-6277d510="">Subscribe</span
          ><!---->
        </button>
      </form>
    </div>
  </section>
</template>

<style scoped>
.newsletter {
  margin: 0 auto;
  max-width: 800px;
  text-align: center;
}
.content {
  padding: 100px 0;
  position: relative;
}
.title {
  color: #000;
  font-size: 32px;
  font-weight: 700;
  line-height: 1.5;
}

.description {
  color: #333;
  font-size: 16px;
  font-weight: 400;
  line-height: 1.5;
}
.form {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  margin: 50px auto 0;
  max-width: 600px;
}
.text-input {
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  border: 1px solid #e9e9e9;
  border-radius: 28px;
  -webkit-box-shadow: 0 3px 7px rgba(0, 0, 0, 0.05);
  box-shadow: 0 3px 7px #0000000d;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  color: #000;
  font-size: 16px;
  font-weight: 400;
  height: 55px;
  line-height: 1.5;
  outline: none;
  padding: 0 25px;
  position: relative;
}
.action-button {
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  background: #0669ff;
  border: none;
  border-radius: 28px;
  color: #fff;
  cursor: pointer;
  display: -webkit-inline-box;
  display: -ms-inline-flexbox;
  display: inline-flex;
  font-size: 16px;
  font-weight: 700;
  height: 56px;
  justify-content: center;
  line-height: 1.5;
  outline: none;
  padding: 0 40px;
  position: relative;
  text-align: center;
  -webkit-transition: background 0.15s ease;
  transition: background 0.15s ease;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.text-input {
  -webkit-box-flex: 1;
  -ms-flex-positive: 1;
  flex-grow: 1;
  margin-right: 20px;
}
.-animation {
  -webkit-transition: all 0.3s ease;
  transition: all 0.3s ease;
}
.-animation {
  -webkit-transition: all 0.3s ease;
  transition: all 0.3s ease;
}
</style>
