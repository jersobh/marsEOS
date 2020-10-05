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
            height="100%"
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
                <br /><br />
                <div class="" style="margin:0 auto;">
                  <q-btn @click="slide='3'" unelevated rounded text-color="grey-10" color="grey-12" label="Continue..." />
                </div>
                <br /><br /><br /><br />
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="2" class="column no-wrap flex-center">
              <div class="q-mt-md text-center">
                "You will complete three missions as a Mars Eos astronaut! The first level is “To know”, where you will gain knowledge about communication in space and related contents. Then you will answer three questions and move on to the “Plan” level. At this level you will learn more about exploring Mars and after answering the questions, you will go to the last step called “Explore”. There you will explore the Red Planet in addition to learning more about it."
                <br /><br />
                <div class="" style="margin:0 auto;">
                  <q-btn @click="slide='3'" unelevated rounded text-color="grey-10" color="grey-12" label="Start mission" />
                </div>
                <br /><br /><br /><br />
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="3" class="column no-wrap flex-center">

              <div class="text-center" style="width:100%;height:100%;">
                <h2>KNOW</h2>
                <div class="" style="margin:0 auto;">
                  <q-btn @click="slide='4'" unelevated rounded text-color="grey-10" color="grey-12" label="Start mission" />
                </div>
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="4" class="column no-wrap flex-center">
              <div class="q-mt-md text-center">
                <h3>Waves</h3>
                <p>
                  Waves can be classified as disturbances that spread from one place to another by both means and vacuum.
                  Those that need a means to propagate are called Mechanical Waves, such as water waves and sound itself, while those that do not depend on a means of propagation are called Electromagnetic Waves such as x-rays, WI- FI and even visible light.
                  The speed of propagation of mechanical waves will vary according to the environment in which they are found.
                  Electromagnetic waves have the speed of light (c), which is 299,792,485 m / s,
                  Therefore, how is this data sent? Find out now.
                </p>
                <h3>How Spatial Communication Works</h3>
                <p>
                  Communication is a process in which information is generated at a point A in space and in time that it receives the name of a source it reaches another point B called a destination.
                  As the distance between this point A and point B increases, the communication processes become more difficult, since the means of propagation are not homogeneous - except for the vacuum - impacting refractions and reflections. When passing through this non-homogeneous medium, part of the energy dissipates in the middle of propagation.
                  As the mechanical waves are limited in terms of the medium, the solution to send information to space is to use electromagnetic waves.
                  Before explaining the electromagnetic waves, it is necessary to understand 2 among some concepts of the waves. Frequency and Wavelength.
                  Frequency is said to be a scalar physical quantity that corresponds to the number of oscillations or cycles that occurred in the interval of 1 second. It is represented by the letter f. And its unit of measurement is Hertz (Hz), in honor of the German physicist Heinrich Rudolf Hertz
                  f = 1 / T
                </p>
                <p>
                  The wavelength is the distance between repeated values ​​between a given cycle. Represented by the Greek letter lambda (ƛ). And its unit of measure is the meter.
                  <b>ƛ = v / f</b>, where v is the speed of the wave.
                  The speed value varies according to the medium in which the wave propagates. Thus, as already mentioned, the speed of the waves is equal to c. And since light is something constant, it is clear why electromagnetic waves can travel through a vacuum.
                  So, putting the values ​​in the formula, we have that <b>f = c / ƛ</b>.
                  In this way, electromagnetic waves obey the inverse proportionality ratio. The longer your wavelength, the lower the frequency and the smaller the ƛ, the higher the frequency.
                  Thus, waves with higher ƛ and low frequencies will have a greater range. While those with shorter wavelengths will do the opposite.
                </p>
                <img
                  src="~assets/5.jpeg"
                  style="max-width:100%;"
                />
                <p>
                  Two topics should therefore be taken into account when choosing the frequency of spatial transmission:
                  Frequencies lower than 30 MHz, may reflect in the ionosphere - layer of the atmosphere with particles charged with ions resulting from solar radiation -.
                  Frequencies higher than the visible spectrum (1016Hz)  such as X-rays, ultraviolet rays and Gamma rays, contain high concentrations of energy and emit ionizing radiation, which are dangerous to health. A harmful radiation when exposed for a long time, being able to break atomic bonds in DNA, causing genetic mutations, known as Cancer.
                  This justifies the choice of UHF antennas chosen by NASA for the Curiosity probe, which was sent to Mars. It operates at a frequency between 300 MHz and 3 GHz, ensuring good range efficiency, less interference and no harmful radiation to man.
                </p>
                <h3>The Deep Space Network (DSN)</h3>
                <p>
                  The basis for space exploration missions is the Deep Space Network (DSN), the largest technological antenna system that enables planet Earth to communicate with Mars and also with other more distant planets. The probes communicate through this system with scientists on Earth. There are 3 complexes around the world in Goldstone, California's Mojave, Desert; near Madrid, Spain; and near Canberra, Australia. This is done to ensure that communication will still occur during the Earth's rotation.
                  For this communication to take place, spaceships are placed to orbit the red planet. The antennas capture the data transmitted by these ships. Through this process, images and other valuable information are periodically received on Earth! Although this mechanism is the most used today, NASA and Cospas-Sarsat (international cooperative) realized that a faster response time and more accurate location data would be needed than this system could offer. As the 70 meter antennas were getting outdated, due to the difficulty of changing the parts, a project to replace them with better and quality antennas are in place. The goal is to update them so that they can have X band uplink capability and X and Ka band downlink capabilities.
                </p>
                <img
                  src="~assets/6.jpeg"
                  style="max-width:100%;"
                />
                <h4>A Deep Space Optical Communications (DSOC)</h4>
                <p>This system is being developed right now as you read this text. It was planned a while ago and can bring many benefits to communication in space. The speed may be greater than the speed of the DSN. It will provide a set of ready-to-fly deep space optical platforms and a composite ground data system, through a terrestrial laser receiver and transmitter that uses existing terrestrial resources. Communications between space and ground will employ new and advanced lasers in the infrared region close to the electromagnetic spectrum. With that, DSOC will be able to provide information rates at least 10 times faster than the usual system. The demonstration of this technology will increase the connectivity speed for future human exploration on Mars and throughout the Solar System. The monitoring capacity will also be much higher, despite long distances. This technology is expected to be tested by launching the instrument that is scheduled for 2022  aboard NASA's Psyche mission.
                </p>
                <img
                  src="~assets/7.jpeg"
                  style="max-width:100%;"
                />
                <h3>ISS communication</h3>
                <p>The space station communicates with the Earth by means of radio frequency signals using a Tracking and Data Relay Satellites (TDRS) system and terrestrial antennas called the Space Network. TDRS are placed in a high orbit above the Earth, in strategic locations so that they can relay data to the ground from anywhere in orbit. The signal is sent to several NASA centers. The software transforms the radio signal into readable data. To send data back, the process is repeated in the other direction. This happens with less than a second of delay in communication. The DSN system can also be used on Mars. The problem is the longest delay in the arrival of data because of the greater distance between Earth and Mars. Lately, NASA has doubled the rate of return of data from the International Space Station to Earth. The ISS now has a 600 megabits per second (Mbps) connection, doubling the amount of data the station can transmit and receive at the same time. Such an improvement in the amount of data can also happen on Mars, as you will see below.
                  </p>
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
<style>
body {
  background: #1d1d1d;
}
</style>
