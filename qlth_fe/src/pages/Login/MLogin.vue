<template>
  <div>
    <div class="m-background-login">
      <div class="m-form-login">
        <div>
          <img
            src="src\assets\logo\hinh-nen-mu-1.jpg"
            alt=""
            width="200"
            height="100"
          />
        </div>
        <div class="h-input">
          <h-input placeHolder="Số điện thoại/Email" typeInput="text"/>
        </div>
        <div class="h-input">
          <h-input placeHolder="Mật khẩu" typeInput="password"/>
        </div>
        <div class="forgot-pass">Quên mật khẩu ?</div>
        <div>
          <button class="h-submit-login">Đăng nhập</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import HInput from "@/components/base/HInput.vue";
export default {
  components: {
    HInput,
  },
};
</script>

<style scoped>
.m-background-login {
  background-image: url("../../assets/img/ranger-4df6c1b6.png");
  background-repeat: no-repeat;
  background-size: cover;
  height: 100vh;

  .m-form-login {
    height: 400px;
    width: 400px;
    background-color: #ffffff;
    position: relative;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
    padding-left: 48px;
    padding-right: 48px;
    box-sizing: border-box;
    border-radius: 8px;

    .h-input {
      margin-bottom: 12px;
    };

    .forgot-pass {
        color: rgb(40, 131, 250);
        font-weight: 500;
        font-size: 14px;
        text-align: left;
    }

    .h-submit-login {
      height: 48px;
      width: 100%;
      background-color: rgb(187, 133, 97);
      border: 0;
      color: #ffffff;
      font-weight: 600;
      margin-top: 24px;
    }
  }
}

img {
  object-fit: cover;
}
</style>