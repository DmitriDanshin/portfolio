<template>
  <section class="contacts">
    <div class="container">
      <div class="contacts__wrapper">

        <div class="contacts__descr">

          <div class="title title_fz36">CONTACT ME</div>
          <div class="divider"></div>

          <div class="title title_fz14 contacts__text">In any way convenient for you:</div>

          <div class="contacts__social">
            <a href="#" class="contacts__link">
              <svg width="30" height="30" viewBox="0 0 30 30" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M25.6055 0L4.39453 0C1.97159 0 0 1.97159 0 4.39453L0 25.6055C0 28.0284 1.97159 30 4.39453 30L13.2422 30L13.2422 19.3945L9.72656 19.3945L9.72656 14.1211H13.2422V10.5469C13.2422 7.63893 15.6077 5.27344 18.5156 5.27344L23.8477 5.27344V10.5469H18.5156L18.5156 14.1211H23.8477L22.9687 19.3945H18.5156V30H25.6055C28.0284 30 30 28.0284 30 25.6055L30 4.39453C30 1.97159 28.0284 0 25.6055 0Z"
                    fill="black"/>
              </svg>

            </a>
            <a href="#" class="contacts__link">
              <svg width="30" height="30" viewBox="0 0 30 30" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M15 30C23.2863 30 30 23.2863 30 15C30 6.71375 23.2863 0 15 0C6.71375 0 0 6.71375 0 15C0 23.2863 6.71375 30 15 30ZM6.86375 14.675L21.3263 9.09875C21.9975 8.85625 22.5837 9.2625 22.3662 10.2775L22.3675 10.2762L19.905 21.8775C19.7225 22.7 19.2337 22.9 18.55 22.5125L14.8 19.7487L12.9912 21.4913C12.7912 21.6913 12.6225 21.86 12.235 21.86L12.5013 18.0438L19.4513 11.765C19.7537 11.4987 19.3837 11.3488 18.985 11.6138L10.3963 17.0212L6.69375 15.8663C5.89 15.6112 5.8725 15.0625 6.86375 14.675Z"
                    fill="black"/>
              </svg>

            </a>
            <a href="#" class="contacts__link">
              <svg width="30" height="30" viewBox="0 0 30 30" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M-9.01547e-07 9.375L-4.09794e-07 20.625C-1.83506e-07 25.8019 4.19812 30 9.375 30L20.625 30C25.8019 30 30 25.8019 30 20.625L30 9.375C30 4.19813 25.8019 7.79513e-07 20.625 1.0058e-06L9.375 1.49755e-06C4.19812 1.72384e-06 -1.12784e-06 4.19813 -9.01547e-07 9.375ZM20.625 2.8125C24.2437 2.8125 27.1875 5.75625 27.1875 9.375L27.1875 20.625C27.1875 24.2437 24.2437 27.1875 20.625 27.1875L9.375 27.1875C5.75625 27.1875 2.8125 24.2437 2.8125 20.625L2.8125 9.375C2.8125 5.75625 5.75625 2.8125 9.375 2.8125L20.625 2.8125Z"
                    fill="black"/>
                <path
                    d="M7.5 15C7.5 19.1419 10.8581 22.5 15 22.5C19.1419 22.5 22.5 19.1419 22.5 15C22.5 10.8581 19.1419 7.5 15 7.5C10.8581 7.5 7.5 10.8581 7.5 15ZM19.6875 15C19.6875 17.5837 17.5837 19.6875 15 19.6875C12.4144 19.6875 10.3125 17.5838 10.3125 15C10.3125 12.4163 12.4144 10.3125 15 10.3125C17.5837 10.3125 19.6875 12.4162 19.6875 15Z"
                    fill="black"/>
                <path
                    d="M7.93685 6.93715C7.93685 6.38521 7.48942 5.93777 6.93748 5.93777C6.38554 5.93777 5.93811 6.38521 5.93811 6.93715C5.93811 7.48909 6.38554 7.93652 6.93748 7.93652C7.48942 7.93652 7.93685 7.48909 7.93685 6.93715Z"
                    fill="black"/>
              </svg>

            </a>
          </div>

          <div class="title title_fz14 contacts__text">Or leave your details and I will write to you myself:</div>

          <form action="" class='contacts__form'>
            <div class="contacts__input">
              <input name="name" id="name" type="text" value="Mark">
              <label for="name">Your name</label>
            </div>

            <div class="contacts__input">
              <input name="email" id='email' type="email">
              <label for="email">Your email</label>
            </div>

            <div class="contacts__textarea">
              <textarea name="text" id="text"></textarea>
              <label for="text">Message</label>
            </div>

            <button class="btn contacts__button">Send</button>
          </form>


        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Contacts-block"
}
</script>

<style scoped>

</style>