### Welcome to my world ! 🌎 🏳️‍🌈

<!--
**nuncio-bitis/nuncio-bitis** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

There is a fifth dimension beyond that which is known to most engineers. It is a dimension as vast as space and as timeless as infinity.  
It is the middle ground between hardware and software, between science and artwork, and it lies between the pit of man's fears and the summit of his knowledge.  
This is the dimension of imagination and creativity.  
It is an area which we call "Embedded Software Engineering".  
That's where I live.

- 🔭 I’ve recently completed a project for my Raspberry Pi 4 that is connected to an ADC, DAC, BME280, and BME6880 via I2C.
    The ADC is converting signals from the 3.3V power supply/battery, the 5V power supply/battery, and a light-sensitive resistor.
    It's based on my **DataGatheringSystem** project, which is an example of gathering information from external sensors. The main
    goal is to take a bunch of C++ concepts I've learned over the years and put them all together into a working system useful
    for learning good software engineering practice.
    
    The code makes use of the C++17/C++2a/C++20 STL and core utilities you'd find on most Linux OSes. So far I can build
    and run the project on Windows, Mac OS Monterey, Ubuntu Linux flavors, and Raspbian (if given stubbing of hardware
    interfaces on non-Raspberry Pi systems, whereas my my **DataGatheringSystem** can be built and run on any system).

    Concepts:
    * Multiple threads controlled by a master thread.
    * A versatile logging system that can maintain logs of a maximum size each, and the total number of log files can
      be constrained (for storage-limited systems)
    * Sensor data storage where the data gathered from sensors maintains its own states of valid, out-of-range, and stale
      (set when data has not been updated within a predetermined amount of time)
    * Subscription to the data storage to be notified on changes.
    * Design documentation to (hopefully) explain the system in detail.

- 🛠 My **Tools** repository contains a lot of useful C++-isms which I've put together while learning C++, and have been
    tuning ever since.

- 🎢 Other repositories are old learning projects or attempts to keep some other people's good work alive.


