Hello Notebook!

1. First meeting: 9/5
   - initial brainstorming on the idea.
   - suggestetd high-level systems and subsystems to see interests and expertise
   - plan initial design ideas (heaadband-ish cap, pcb, electrodes wired neatly around cap)
   - Idea post made by Nikhil
  
2. Second meeting: 9/9
   - Since no replies to idea post, met with indian prof, and asked for opinion
   - Prof feedback was studied and taken into account
       - false-negative and false-positive rates
       - comparison with modern sleep-detecting methods(cameras in cars etc)
       - seemlessness of design
       - sleep detection algorithm 
   - prof feedback was studied and included in rfa draft
   - posted RFA
  
3. 3rd meeting: 9/14
   - proposal planning and discussion
   - drafted proposal
   - finalised high-level block diagram and subsystems as given below:
     <img width="846" height="406" alt="Screenshot 2025-09-14 at 18 11 18" src="https://github.com/user-attachments/assets/b5be6066-7c5a-45f6-a4e4-950ded320607" />
   - looked through online for components and prices estimate:
<img width="574" height="349" alt="Screenshot 2025-09-16 at 16 20 25" src="https://github.com/user-attachments/assets/1d28e088-35c1-4e89-ab02-ad1e8892c59d" />

4. Meeting TA 9/16
   - Work on subsystem requirements, almost same as system requirement, but be more specific with the components
   - Can use the ADS1229 chip instead since we are still wiring it and its only a chip and not a whole on-board chip.
   - Work on proposal, seem like we are on the right road.
  
5. 4th meeting: 9/19
   - Prepared Proposal together with Nikhil.
   - Worked on the overleaf formatting, and design for power, signal acquisition, and alarm systems.
   - Understand complexities of power system such as battery ratings for enough battery life; battery size; battery safety management and buck converter.
   - Finished our team contract for the class
   - Made more detailed block diagram with components and power ratings for easier power system design
   <img width="584" height="418" alt="block_diagram" src="https://github.com/user-attachments/assets/5e6cb6be-e4e9-404a-94a1-87239125517a" />

6. Proposal 9/22
   - We finished up all the work for the proposal and proposed our project for the class.
   - We divided the work and decided that as immediate action, we will design the PCB and its schematics. I chose to do the battery management, converter, and ADS1299 module, while Nikhil will work on the STM32 module and firmware.

7. Schematics 10/1
   - I was working on the schematics seperately.
   - I finished up with BMS, buck and boost converters, and the ADS1299 module.
   <img width="1264" height="712" alt="image" src="https://github.com/user-attachments/assets/fe975662-5a37-4518-ad48-d78720bfde7e" />
   <img width="881" height="492" alt="image" src="https://github.com/user-attachments/assets/ece036aa-0bdc-45c7-8862-7c8bdfb910ef" />
   <img width="634" height="224" alt="image" src="https://github.com/user-attachments/assets/6b6ac8fc-a3fc-420d-8e7c-70f6e68c8849" />
   <img width="518" height="224" alt="image" src="https://github.com/user-attachments/assets/62da060d-6e8a-46ce-b18d-391c11e4d311" />
   <img width="564" height="433" alt="image" src="https://github.com/user-attachments/assets/ee5666b1-c0e6-44db-abc0-70dab80a6df7" />

8. Parts order 10/3
   - Me and Nikhil discussed what parts and components we will be buying and put in our first orders for the components that encompasses the allocated $100. 
<img width="413" height="202" alt="Screenshot 2025-12-11 at 18 58 14" src="https://github.com/user-attachments/assets/6a1cbc8d-abc6-4b92-8a5b-763a8d514b1e" />

9. PCB Design plan 10/10
   - I figure out the PCB design for the ADS1299(limited free resources for PCB design).
<img width="1832" height="1204" alt="image" src="https://github.com/user-attachments/assets/1d18dd1d-ecb7-42ae-a587-769e50a9ce11" />

10. Design Document 13/10
   - Nikhil and I met up to finish up our design document and finalise our requirement and verification table.

11. PCB Design 16/10
   - Nihkil and I spent most of the day designing our PCB at Grainger Engr library. Due to the 10cm*10cm size limit, we planned to put it all in the same PCB.
   - We finished the PCB, ran the test on PCBway and submitted our gerber files to Zhuoer.
   <img width="413" height="276" alt="Screenshot 2025-12-11 at 18 59 53" src="https://github.com/user-attachments/assets/16dd259d-0967-4b4b-9576-beff33e90c7b" />

12. Breadboard Demo test 25/10
   - Nikhil and I met up to plan and decide what we'll be doing for the breadboard demo since we have not received our PCB, and our parts. We used some available resistors and the only part we had, the buzzer, to show some physical representation of what we have planned to achieve.
   - We build a simple (low-dropout)LDO converter to show how we plan to get the 3.3V and 5V rails.
   - Nikhil planned to show how we will be using the buzzer to make the alerts, and how they are low powered.
   
13. Breadboard Demo 28/10
   - Nikhil and I did our breadboard demo as planned. We showed some progress, but nothign significant.

14. Bill of Material 30/10
   - We did the planning for what components we need to buy, and where we are going to buy them. An excel sheet called bill of material, as it was easy to keep track of what we want to get.
<img width="1430" height="453" alt="Screenshot 2025-12-11 at 19 18 36" src="https://github.com/user-attachments/assets/7b2a6f7a-c44a-49af-aa61-45435270f2d8" />

15. Component order 31/10
   - Nihkil put in the order for the material on Digikey, and sent Zhuoer the parts that we planned to get from the ECE shop.
<img width="402" height="262" alt="Screenshot 2025-12-11 at 19 21 42" src="https://github.com/user-attachments/assets/bd76e713-7a4d-445c-9731-38ec18064ad5" />









