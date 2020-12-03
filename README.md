# WakeUp
Inspiration
Keeping drivers awake at the wheel.

# What it does
Uses a special camera with facial-attention software to detect a sleepy driver. This event instigates a stimulus to the driver to help them stay awake.
# How we built it
We used machine learning data-sets to attain data on eyelid-level and ear-level proportions to accurately predict when a driver is falling asleep. We utilized Python-based libraries such as OpenCV, dlib, and imutiles to bolster our facial-recognition program. The result was real-time eye-tracking and near-perfect operation, even in low-light settings.

Once WakeUp! recognizes a sleepy driver, it sends out a stimulus in the form of a low hum (The Hum Phenomenon) and an SMS message (using the amazing Twilio API). Both of which, grab the immediate attention of the driver and keeps them alert of their surroundings.

# Challenges we ran into
We had lots of trouble troubleshooting the Rasberry Pi with a depth-sensing camera and being able to compile the correct Python libraries for the project. This project was also the first time our team had used SSH on Raspberry Pi and Twilio, the latter of which we were very excited to learn.

One of the biggest challenges we faced was setting up our laptop as an external display for the Raspberry Pi. We had to set up a VNC server over the network to allow the Pi to communicate with our Macbook.

# Accomplishments that we're proud of
Being able to integrate the specialized camera and the Raspberry Pi together in real-time with our software, which was comprised of OpenCV, dlib, Twilio, imutiles, and a couple more APIs.

# What we learned
Patience is key. But besides that, we learned how to effectively manage several APIs with a Logitech camera and the Raspberry Pi.

# What's next for WakeUp!
We would like to conduct more trials and improve our algorithm beyond the ~95% success-rate our machine currently boasts. Beyond that, we would like to work with auto-shops and small companies about implementing a WakeUp!-similar solution that could end up in our community's automobiles.

The goal of WakeUp! is to bring awareness to a prevalent problem in the United States and to provide a viable solution.

# Built With
*opencv*, 
*dlib*, 
*python*, 
*raspberry-pi*, 
*Intel realsense* 
