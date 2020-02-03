<template>
  <div>
    <q-page
      :style="
        $q.dark.isActive
          ? 'background-image: linear-gradient(to top, #30cfd0 0%, #330867 75%);'
          : 'background: #FFEFBA; background: -webkit-linear-gradient(to bottom, #FFFFFF, #FFEFBA); background: linear-gradient(to bottom, #FFFFFF, #FFEFBA 65%);'
      "
    >
      <div class="column items-center">
        <q-card
          class="my-card"
          :style="
            $q.dark.isActive
              ? 'background-image: linear-gradient(-220deg, #FF057C 0%, #8D0B93 50%, #321575 100%);'
              : 'background-image: linear-gradient(-40deg, #FFC796 0%, #FF6B95 100%)'
          "
        >
          <q-card-section>
            <div class="column items-center text-center">
              <div class="text-h3" style="padding-bottom: 3%; padding-top: 2%">
                Pet Partners
              </div>

              <div
                class="text-h5"
                style="padding-bottom: 3%; padding-top:10px; padding-right: 3%; padding-left: 3%"
              >
                😻 Pet Partners 😸 is a fictional Pet Rental Service created by
                my daughter.
              </div>
              <div
                class="text-h5"
                style="padding-bottom: 3%; padding-top:10px; padding-right: 3%; padding-left: 3%"
              >
                She is the ⭐️ of my life!
              </div>
              <div
                class="text-h5"
                style="padding-bottom: 3%; padding-top:10px; padding-right: 3%; padding-left: 3%"
              >
                😻 Pet Partners 😸 will aggressively market to anyone having a
                bad day 😭.
              </div>
              <div
                class="text-h5"
                style="padding-bottom: 3%; padding-top:10px; padding-right: 3%; padding-left: 3%"
              >
                The mission of 😻 Pet Partners 😸 is to brighten 🌈 people's day
                with our loving pets.
              </div>
            </div>
          </q-card-section>
        </q-card>

        <q-space />
        <div class="space"></div>

        <q-card
          class="my-card"
          :style="
            $q.dark.isActive
              ? 'background-image: linear-gradient(-230deg, #FF057C 0%, #8D0B93 50%, #321575 100%);'
              : 'background-image: linear-gradient(-45deg, #FFC796 0%, #FF6B95 100%)'
          "
        >
          <q-parallax src="statics/pug-frown.jpg" :height="400">
            <q-btn
              class="absolute-top-right"
              to="/"
              color="white"
              icon="chevron_right"
              label="Puppy Rentals"
              flat
            />
          </q-parallax>

          <q-card-section>
            <div
              class="text-h4"
              style="padding-bottom: 1%; padding-top:10px; padding-right: 3%; padding-left: 3%"
            >
              Rent-a-Pug
            </div>
            <div
              class="text-h5"
              style="padding-bottom: 2%; padding-top:10px; padding-right: 3%; padding-left: 3%"
            >
              Hold puppies whenever you get the chance. You will thank us later.
            </div>
          </q-card-section>
        </q-card>

        <div class="space"></div>

        <q-card
          class="my-card"
          :style="
            $q.dark.isActive
              ? 'background-image: linear-gradient(-230deg, #FF057C 0%, #8D0B93 50%, #321575 100%)'
              : 'background-image: linear-gradient(-45deg, #FFC796 0%, #FF6B95 100%)'
          "
        >
          <q-parallax src="https://placekitten.com/1920/1280" :height="400">
            <q-btn
              class="absolute-top-right"
              to="/"
              color="white"
              icon="chevron_right"
              label="Kitten Rentals"
              flat
            />
          </q-parallax>

          <q-card-section>
            <div
              class="text-h4"
              style="padding-bottom: 1%; padding-top:10px; padding-right: 3%; padding-left: 3%"
            >
              Kitten Rentals
            </div>
            <div
              class="text-h5"
              style="padding-bottom: 2%; padding-top:10px; padding-right: 3%; padding-left: 3%"
            >
              Kittens can happen to anyone.
            </div>
          </q-card-section>
        </q-card>
      </div>
    </q-page>
  </div>
</template>

<style lang="scss" scoped>
.my-card {
  width: 80%;
  margin-top: 5%;
  margin-bottom: 5%;
}
</style>
