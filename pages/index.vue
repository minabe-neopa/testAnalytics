<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div class="text-center">
        <logo />
        <vuetify-logo />
      </div>
      <v-card>
        <v-card-title class="headline">
          ログイン前のページです。
        </v-card-title>
        <form action="" method="post">
          <label>
            メールアドレス
            <input type="email" name="mail">
          </label><br>
          <label>
            パスワード
            <input type="password" name="pass">
          </label><br>
          <input type="submit" name="送信">
        </form>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
