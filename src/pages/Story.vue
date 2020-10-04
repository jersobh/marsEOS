<template>
  <q-page class="flex flex-center">
    <q-carousel
            v-model="slide"
            transition-prev="jump-right"
            transition-next="jump-left"
            swipeable
            animated
            control-color="orange"
            prev-icon="arrow_left"
            next-icon="arrow_right"
            navigation-icon="radio_button_unchecked"
            navigation
            arrows
            height="90vh"
            width="100%"
            class="text-white shadow-1 rounded-borders"
          >
            <q-carousel-slide name="1" class="column no-wrap flex-center">
              <img
                alt="Quasar logo"
                src="~assets/1.jpeg"
                style="max-width:100%;"
              />
              <div class="q-mt-md text-center">
                What would the world be like if human beings were unable to communicate? Fortunately, since the beginning of human history, techniques for sharing information have been developed, integrating localities and cultures. On the other hand, the process of transmitting messages connects us as a human race. Now, we've come this far, through the Internet, to you. Most people are often connected on the planet, which makes geographical distances smaller in a way. But is it possible to narrow the long distance between planet Earth and the planet Mars following this example? Well, fortunately we can say that technology is growing at a steady pace. It's literally accelerating! So how are we getting to Mars? How can I collect data? How to prepare the planet for the arrival of human beings? For each of these questions, there is an answer. Come with us and learn more about how communication between the planets is and how they are involved with our future. Here you will begin your journey to an interplanetary mission. Welcome to The Mars Eos and get ready for a new dawn. On Mars!
                <br /><br /><br /><br />
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="2" class="column no-wrap flex-center">
              <div class="q-mt-md text-center">
                "You will complete three missions as a Mars Eos astronaut! The first level is “To know”, where you will gain knowledge about communication in space and related contents. Then you will answer three questions and move on to the “Plan” level. At this level you will learn more about exploring Mars and after answering the questions, you will go to the last step called “Explore”. There you will explore the Red Planet in addition to learning more about it."
                <br /><br />
                <div class="" style="margin:0 auto;">
                  <q-btn to="/story" unelevated rounded text-color="grey-10" color="grey-12" label="Start mission" />
                </div>
                <br /><br /><br /><br />
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="3" class="column no-wrap flex-center">
              <img
                alt="Quasar logo"
                src="~assets/4.jpeg"
                style="max-width:100%;"
              />
              <div class="q-mt-md text-center">

              </div>
            </q-carousel-slide>
          </q-carousel>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex',
  data () {
    return {
      slide: '1'
    }
  }
}
</script>
