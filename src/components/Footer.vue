<template>
    <v-footer
      class="bg-transparent text-center d-flex flex-column"
    >
      <div>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          :icon="icon"
          class="mx-4"
          variant="text"
        ></v-btn>
      </div>
  
      <div class="pt-0">
        <p style="font-size: 11px; letter-spacing: 1px;">Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore quaerat atque tempore. Harum quo temporibus enim voluptatibus sequi cupiditate. Dolorem, autem reiciendis. Sequi exercitationem consequatur enim repudiandae! Eius, ex quia quos ipsam atque qui architecto. Cumque, nostrum facilis veritatis nam rem a est omnis accusantium inventore eum. Inventore labore obcaecati, dolorem omnis quasi ratione sit possimus. Corporis veritatis quo, quibusdam molestias facere similique sed amet? Minima, necessitatibus aspernatur. Nisi cum ut debitis itaque ex! Tenetur deserunt voluptas, obcaecati iste pariatur blanditiis? Tempora nemo dolores praesentium aperiam consectetur, temporibus omnis nisi facilis magni unde inventore earum qui blanditiis commodi aliquid harum?</p>
       
      </div>
  
      <v-divider></v-divider>
  
      <div>
        {{ new Date().getFullYear() }} — <strong>Developed by RB</strong>
      </div>
    </v-footer>
  </template>
  <script>
    export default {
      data: () => ({
        icons: [
          'mdi-facebook',
          'mdi-twitter',
          'mdi-linkedin',
          'mdi-instagram',
        ],
      }),
    }
  </script>