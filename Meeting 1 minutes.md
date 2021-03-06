# Coming up

- Meet on Saturday at noon to play with LEGO

- D, P will go to hardware tutorial (Kr can't make it)
- Everyone will go to design tutorial + architecture lecture

- Team Leaders will plan use cases by Monday (P will arrange meeting via when2meet)

- For now, focussing on LEGO and physical design and moving (combo of firmware, LEGO and comms), much less on vision, planning and strategy

- N suggests having all 3 parts kinda working by week 3


# Allocations

- Experience:
    - J: Lots with Python, some with Java, wee bit of hardware
    - Kr: Lots of hardware + Python, worked with Python all summer
    - P: Lots with Python, some with Java, some with intelligent agents, maths
    - T: Lots with Python, some with Java, some with intelligent agents, maths
    - D: Lots of C, some hardware + sensors, some Java, some Python
    - Ka: Touch of hardware (PBASIC during higher tech studs), Java, python, 
- Roles:
    - N suggestion to keep it fluid but have roles allocated nonetheless
    - Kr likes hardware!  Yay!
    - N suggests 2 folk per group (fluidly)
    - N suggests at least one person in charge of overall robot structure/physical design
    - Main areas spotted:
        - Vision - T leading, Kr, J, D involved
        - Planning - P leading, T, Kr involved
        - Strategy - Everyone
        - Comms - J leading, P involved
        - Firmware - Kr leading, D & Ka involved
        - Sensors - D leading
        - LEGO - P leading, EVERYONE involved
        - Reports - Ka leading, EVERYONE involved
- Group management:
    - One manager at a time, changing every so often
    - P and J volunteering, P for now (Ka volunteers too)
- Team management:
    - Can mainly ignore til next milestone
    - Someone should be nominated to be head of comms with them - probably the manager

# Design

- General design:
    - T suggests writing overall design before code esp API
    - N suggests not as important as lots will be learned and changed
    - T clarifies more wanting to plan use cases
    - P suggests each leader creates use cases by Monday
- Wheels: 
    - N suggests only holonomics
    - J suggests reverse reliant robin
- Sensors:
    - "Adding extra sensors is easy cos I'm awesome" - Kr
    - Kr: vision should be main sensor
    - D: distance sensor should be more prominent
    - possible IR sensors: 
        (0.5 - 15cm range) http://www.robotshop.com/uk/pololu-carrier-sharp-gp2y0d815z0f-ir-range-sensor-05-15cm.html
        (2 - 10cm range) http://www.robotshop.com/uk/dfrobot-gp2y0d180z-2-10cm-range-sensor.html (with Arduino cable)
    - line tracking sensor for Arduino: http://www.robotshop.com/uk/dfrobot-line-tracking-sensor-for-arduino.html

- Main things not to change after initial design: wheel type + location, weight (too much).  Changing these would require major tweaks to the firmware code.  
    
# Language
-    Vision will be done in Python (it has openCV)
-    Arduino uses C-ish stuff
-    For other bits, Python and Java both suggested
-    Python is nicer, Java is used more in previous years
-    Python more popular with us, so we'll use that
-    Stick to reasonable coding standards (roughly PIP), but no need to be too strict

# GitHub
-    P has set up repo (https://github.com/pbsinclair42/SDP-2016)
-    Private for now
-    Might share with other group after milestone 1

# Slack
-    SDP wide slack may be happening
-    J will make a Slack group in the meantime

# Other

- Group space (/group/teaching/sdp/sdp4) may be available soon, but we'll probably just be sticking to Git anyway

- Kr has labs finishing at 2pm on Wednesdays so will be slightly late to some milestones, but that'll be fine
