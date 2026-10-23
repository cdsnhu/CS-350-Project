# CS-350-Project
CS 350 Final Project

### Summarize the project and what problem it was solving.
The project was to construct a prototype embedded system for SysTech: A low-level thermostat that was able to respond to different temperature readings. The end goal was to give the device Wi-Fi capability to wireless upload data into a cloud.

### What did you do particularly well?
After a bit of trial and tribulation, I was able to construct the device on the breadboard with relatively ease. Breadboards aren't so scary after understanding the basics.

### Where could you improve?
I'd like to understand the "StateMachine" library a bit more. There's plenty of potential and powerful tools that the library can provide 
I like how some of the functions that are designed for upon 'entry' and 'exit' of a state, which makes it easier to configure and make the device do react specifically at which time.

### What tools and/or resources are you adding to your support network?
Because the project specifically request Wi-Fi connectivity to send data to the cloud, there are some options to choose from: 
  an HTTPS API could be implemented to have it send it in JSON format
  Use MQTT: a lightweight IoT library that is specifically design with IoT in mind.
  
### What skills from this project will be particularly transferable to other projects and/or course work?
State Machine UML design, electronical skills, Raspberry Pi configuration, embedded system familiarity

### How did you make this project maintainable, readable, and adaptable?
Keep detailed documentation and record what changes have occurred at each revision/iteration.
Put notes into the python code to help others read how the code should operate.
Use UNL diagrams to simplify and showcase in layman terms the standard procedure of the code.

