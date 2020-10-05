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
                <h4>Waves</h4>
                <p>
                  Waves can be classified as disturbances that spread from one place to another by both means and vacuum.
                  Those that need a means to propagate are called Mechanical Waves, such as water waves and sound itself, while those that do not depend on a means of propagation are called Electromagnetic Waves such as x-rays, WI- FI and even visible light.
                  The speed of propagation of mechanical waves will vary according to the environment in which they are found.
                  Electromagnetic waves have the speed of light (c), which is 299,792,485 m / s,
                  Therefore, how is this data sent? Find out now.
                </p>
                <h4>How Spatial Communication Works</h4>
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
                <h4>The Deep Space Network (DSN)</h4>
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
                <h4>ISS communication</h4>
                <p>The space station communicates with the Earth by means of radio frequency signals using a Tracking and Data Relay Satellites (TDRS) system and terrestrial antennas called the Space Network. TDRS are placed in a high orbit above the Earth, in strategic locations so that they can relay data to the ground from anywhere in orbit. The signal is sent to several NASA centers. The software transforms the radio signal into readable data. To send data back, the process is repeated in the other direction. This happens with less than a second of delay in communication. The DSN system can also be used on Mars. The problem is the longest delay in the arrival of data because of the greater distance between Earth and Mars. Lately, NASA has doubled the rate of return of data from the International Space Station to Earth. The ISS now has a 600 megabits per second (Mbps) connection, doubling the amount of data the station can transmit and receive at the same time. Such an improvement in the amount of data can also happen on Mars, as you will see below.
                  </p>
                <h4> How will astronauts be able to use internet on mars?</h4>
                <p>
                  They can use it one day when some technologies are deployed. DTN (Delay / Disruption Tolerant Networking), which is already being tested on the ISS, consists of a system that sends information in certain "packets", having the ability to establish communication between multiple network nodes separated by millions of kilometers of distance. This connection will be formed by several network nodes located somewhere in space on the Moon, Mars or a spacecraft orbiting the Earth and elsewhere. So it will be possible to have internet on Mars in the future. This whole project is part of an even bigger plan, The Solar System Internet (SSI). NASA will make use of three networks formed by ground stations and also by several relay satellites. They are: Deep Space Network (DSN), Near Earth Network (NEN) and Space Network (SN). When operating in conjunction with other terrestrial nodes, these networks will form the Internet of the Solar System.
                </p>
                <img
                  src="~assets/8.jpeg"
                  style="max-width:100%;"
                />
                <h4>X-rays in obtaining data, how can they be useful?</h4>
                <p>An innovative method has been developed by NASA and has already been tested on the ISS. Communication can suffer less latency through X-rays. In this process, ultra-regular pulsar oscillations are used to acquire time and location data. What are pulsars? Well, these pulsars are neutron stars. Through them it is possible to calculate the position of a spacecraft in space by comparing the estimated pulse arrival time with the observed pulse arrival time, combined with navigation software. How is it possible to know where some pulsars are located? It is possible to find out the time and location of ships outside the region close to Earth. This represents a great achievement for the advancement of space exploration! Using this type of communication, it would be possible to launch spaceships for greater distances and with more autonomy, achieving good communication.</p>
                <h4>Infrared lasers: outside the cinema screens, but with a leading role</h4>
                <p>Optical communications have a great potential for data transmission and in this case, there is a data transmission project aimed at using infrared lasers. This is one of the methods that can minimize the problems of delayed data arrival. This data rate can be 10 to 100 times higher than what occurs in radio frequency communication systems already used. In this way, spacecraft with optical communications systems will enable quality data to be brought back to Earth. Despite this, the Laser Communications Relay Demonstration (LCRD) can still be interrupted by atmospheric interference, such as clouds. If it is cloudy, the system needs to wait until the ambient conditions are adequate to be able to transmit the data. To avoid delays, services can be transferred to another ground station, in addition to the current station in Hawaii that works on this project.
                </p>
                <h4>Global Navigation Satellite System</h4>
                <p>
                  There is another innovative technology that can improve interplanetary communication. The GNSS satellites (Global Navigation Satellite System) are being developed. They have search and rescue instruments that enable more advanced calculations that offer better accuracy. These satellites will be spread in large numbers in the future.
                </p>
                <h4>Space Network</h4>
                <p>The Space Network update is taking place recently. A new terrestrial digital architecture is being built for the Space Network. Technicians updated the space station's components and software. All these changes provide the improvement of data processors in several NASA centers, as well as routers, interfaces and others. The circuits and bandwidth of the data lines have been improved, being a very important part of this project.
                </p>
                <img
                  src="~assets/9.jpeg"
                  style="max-width:100%;"
                />
                <h4>Bandwidth and speed</h4>
                <p>Normally, in the Deep Space Netwok, signals are transmitted and received in two radio frequency bands: S-band (2 GHz) and X-band (8 GHz). The radio signals, travelling at the speed of light, took up to 50 minutes to cover the distance between the spacecraft and Earth! (ESA website) The signals transmitted by the antennas on the probe are picked up by the DSN system. There are three different antennas attached to the probes that are orbiting Mars at the moment.
-The low gain is connected to a radio that takes longer. It is capable of transmitting a small data rate to other orbiting probes on Mars or also to Earth. This antenna is designed to be used in emergency situations if other transmission devices fail.
-The high gain antenna is connected to a high speed UHF radio. This antenna is the main one in the communication, in turn transmits the information quickly. (rates range from 256 kbits / s to 2 Mbits / s and the antenna consumes 15 watts, which is not much).
-The high gain antenna is a direct means of communication and works for three hours a day, mainly due to the alignment of the planets. This antenna uses a radio that consumes 40 watts and transmits only 12 kilobits per second. There is a delay of 20 minutes in the transmission of information, as the signal must travel distances greater than 100 to 400 million kilometers between Earth and Mars. NASA uses it to send commands to the probe and also to receive emergency data.
The Deep Space Optical Communications (DSOC) is superior to Deep Space Network (DSN) and is being developed. Signals are transmitted and received in two radio frequency bands: S-band (2 GHz) and X-band (8 GHz). The radio signals, traveling at the speed of light, took up to 50 minutes to cover the distance between the spacecraft and Earth!
</p>
<img
  src="~assets/10.jpeg"
  style="max-width:100%;"
/>
              <h4>The sun and its interference</h4>
              <p>The Sun is mainly composed of Helium and Hydrogen gases. And its surface temperature is approximately 5778 Kelvin (K). However, close to the core it is estimated that this temperature will reach 15,000,000 Kelvin.
At high temperatures like these, atoms lose their electrons without an electrosphere, leaving the nuclei isolated from neutrons and protons, which increases the chance of collisions.
When two protons collide, they attract each other to form a Hydrogen nucleus and a positron (electron antiparticle).
A Hydrogen nucleus then joins with a proton generating a Helium nucleus that emits a certain electromagnetism.
Finally, two unstable Helium nuclei unite to form a stable Helium nucleus and two protons.
</p>
<img
  src="~assets/11.jpeg"
  style="max-width:100%;"
/>
<p>Hydrogen generating energy that is emitted in the form of light, heat and radiation.
This process is called Nuclear Fusion.
The process is reflected on its surface and one of its results is sunspots conceptualized as cold regions. These are capable of generating large magnetic disturbances, which in turn, generate an Electromagnetic Interference (EMI) that cause noise that interferes with the transfer of information.
This has been one of the greatest challenges in interplanetary communication in the Solar System, because when the Sun is aligned between the Earth and another planet,
receiving and sharing data is extremely difficult.
</p>
<h3>Solution proposed by Mars Eos</h3>
<p>Although we don't have enough technology yet, a possible solution could be the creation of 3 or 4 stations with angles of 60º or 90º to each other in relation to the orbit of the planets that are capable of relaying the signal from Earth to Mars and operating with photovoltaic plates to feed the energy. A navigation system based on gyroscopes could be used to conserve angular momentum to make them inert in the Solar System's framework and also use some mechanism that uses the energy generated by the plate to generate torque in the gyroscope with sufficient force to compensate for the effects of dynamic friction. Thus, even with an increase in time for retransmission, there would be no more interference from the sun and data would be better used.
</p>
<div class="" style="margin:0 auto;">
  <q-btn @click="slide='5'" unelevated rounded text-color="grey-10" color="grey-12" label="Take the test" />
</div>
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="5" class="column no-wrap flex-center">
              <div class="q-mt-md text-center" style="width:100%;">
                <p>1- Choose the option that matches the content you read at that level</p>
                <div class="" style="margin:0 auto;">
                  <q-btn ref="1-1" @click="wrong($event, '1-3')" unelevated rounded text-color="grey-10" color="grey-12" label="a) Infrared lasers are not recommended for use in communication, it would be impossible to use them." />
                </div>
                <div class="" style="margin:0 auto;">
                  <q-btn ref="1-2" @click="wrong($event, '1-3')" unelevated rounded text-color="grey-10" color="grey-12" label="b) DSN has antennas in only one location, as it is enough for this method of communication." />
                </div>
                <div class="" style="margin:0 auto;">
                  <q-btn ref="1-3" @click="correct($event);slide='6'" unelevated rounded text-color="grey-10" color="grey-12" label="c) When the Sun is aligned between the Earth and another planet, receiving and sharing data is extremely difficult." />
                </div>
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="6" class="column no-wrap flex-center">
              <div class="q-mt-md text-center" style="width:100%;">
                <p>2- Choose the option that matches the content you read at that level</p>
                <div class="" style="margin:0 auto;">
                  <q-btn ref="2-1" @click="correct($event);slide='7'" unelevated rounded text-color="grey-10" color="grey-12" label="a) There are at least three different antennas attached to the probes that are orbiting Mars at the moment." />
                </div>
                <div class="" style="margin:0 auto;">
                  <q-btn ref="2-2" @click="wrong($event, '2-1')" unelevated rounded text-color="grey-10" color="grey-12" label="b) The probes normally use only one antenna, so the probe is not too heavy. Having only one antenna is positive." />
                </div>
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="7" class="column no-wrap flex-center">
              <div class="q-mt-md text-center" style="width:100%;">
                <p>3- Choose the correct option:</p>
                <div class="" style="margin:0 auto;">
                  <q-btn ref="3-1" @click="correct($event);slide='8'" unelevated rounded text-color="grey-10" color="grey-12" label="a) The UHF antennas operate at a frequency between 300 MHz and 3 GHz, ensuring good range efficiency and less interference and no harmful radiation to man." />
                </div>
                <div class="" style="margin:0 auto;">
                  <q-btn ref="3-2" @click="wrong($event, '3-1')" unelevated rounded text-color="grey-10" color="grey-12" label="b) UHF antennas cause danger to humans due to high radioactivity, making them rarely used in space missions." />
                </div>
              </div>
            </q-carousel-slide>
            <q-carousel-slide name="8" class="column no-wrap flex-center">
              <div class="q-mt-md text-center" style="width:100%;">
                <h3>CONGRATULATIONS</h3>
                <p>You're now ready to explore Mars.</p>
                <div class="" style="margin:0 auto;">
                  <q-btn to="/orbit" unelevated rounded text-color="grey-10" color="grey-12" label="Keep tracking your route" />
                </div>
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
  },
  methods: {
    correct: function (event) {
      console.log(event)
    },
    wrong: function (event, ref) {
      event.target.style.background = "red"
      this.$refs[ref].style.background = "green"
      console.log(event)
    }
  }
}
</script>
<style>
body {
  background: #1d1d1d;
}
</style>
