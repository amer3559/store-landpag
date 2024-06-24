<template>
  <div class="banner">
    <div class="parent">
      <v-container>
        <V-row>
          <v-col cols="6">
            <div class="cont">
              <h3><span>Huge Saving</span> on UHD Televisions</h3>
              <p class="hint">Sale up to 70% off on selected items*</p>
              <v-btn
                variant="outlined"
                class="px-10 py-4"
                density="compact"
                style="border-radius: 30px; text-transform: none; height: unset"
              >
                Shop Now
              </v-btn>
            </div>
          </v-col>
        </V-row>
      </v-container>
    </div>
  </div>
</template>

<style lang="scss">
.banner {
  .parent {
    height: 390px;
    background-image: url(../../assets/images/banner-bg.jpg);
    background-size: cover;
    background-position: -60px top;
    .cont {
      color: white;
      padding: 40px 0 0 100px;
      h3 {
        font-size: 45px;
        font-weight: 900;
        span {
          color: rgb(45 251 223);
        }
      }
      .hint {
        margin: 20px 0 40px;
      }
    }
  }
}
</style>
