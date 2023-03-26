# training_mavlink_intro
Mavlink and Ardupilot Introduction training exercise

In this exercise you will learn about the wonders of ardupilot, mavlink and the drone's hobbiest community! 

A silly lady Amy and her friend Tammy wants to fly a drone. 
They look on the internet and find that ardupilot is a firmware running on pixhawk which supposedly should help them fly drones. 

While they wait for their drone to arrive from AliExpress, they want to check the firmware on some simulation on their pc. 

Remember! Amy and Tammy are not SW engineeers nor even mechanics engineer, they are just two hobbiests starting to get into the drones world. 

They are enthusiastics and quick learners with an eager desire to learn this world, and they have the whole **World Wide Web** in the palm of their hand. 

You are now inside Amy and Tammy's shoes, Enjoy! 


## Phase 1: 

1. Install gcs (ground control station) to command your drone. This link might help you - https://ardupilot.org/copter/docs/common-install-gcs.html

2. Install sitl (software in the loop) to simulate the ardupilot software in an emulator. This link might help you - https://ardupilot.org/dev/docs/sitl-simulator-software-in-the-loop.html

3. Run the drone in sitl and connect your gcs to it (you're a big girl now, you don't need another help links). 

4. Takeoff your drone, and set it to go **autonomously** to another location on the map. 

5.  Answer the following questions and complete the next tasks using the GCS and the internet (Do not make use of Mavproxy yet, you'll learn about it in just  a minute). Operators use the GCS as their main source to interact with the pixhawk, and there are many features the GCS gives you, so get inside their shoes and use the time to get to know it - 

    - Which mode did you change to? Was there any problem taking off / go to another location? 

    - Change the height at which the drone goes to another location. 

    - Name 4 modes of the copter and understand their meaning! 

6. Great! you have guided your first drone in simulation, Hooray!

7. Answer the following questions - 
    
    - Why is it important to arm your vehicle? (safety wise)

    - How can we override the need for it, and when should we do it? Why is the vehicle being disarmed automatically after a few seconds? how can we change this? 

    - To understand a little bit more about paramateres in ardupilot - find the full list of parameters in your GCS app. LOTS of them ah? 

    - Find the paramter responsible for arming. make your drone run without the need of arming. 

    - You now have some understanding of parameters and their usage in ardupilot.


--------------------------------------------------------
DO NOT GO DOWN BEFORE UNDERSTANDING THIS FROM THE GCS! 

HAVE YOU REALLY UNDERSTOOD THE ABOVE QUESTIONS? 
....

NOW YOU CAN KEEP GOING 

--------------------------------------------------------


## Phase 2: 

1. You're programmeres aren't you? so CLI should feel natural to you than this weird GCS. 

2. Lucky for you there is a tool like this - called MAVProxy! 

3. Install it and then repeat the takeoff and go to exercise using it. 

4. Feel the application and the options it gives you. 

5. use it along side the GCS. meaning for example - takeoff from one application and guide the drone from the other one (without closing / disconnecting one from antoher). 

6. Answer - 

    - How does the ardupilot can listen from both of these applications ? 
 

## Phase 3: 

