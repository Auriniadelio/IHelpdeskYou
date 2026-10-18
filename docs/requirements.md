# Requirements

## Functional requirements (what the system must DO)
1. The system shall execute a Finite State Machine (FSM) to manage state transitions across distinct gameplay phases (e.g., Main Menu, Workstation Shift, Personal Phone Break, Ticket Diagnostic Mode, and Shift Summary).
2. The system shall render incoming helpdesk support tickets containing raw evidence artifacts, including spoofed emails, audio call transcripts, SMS screenshots, and malicious pop-up advertisements.
3. The system shall provide diagnostic inspection tools (including a domain lookup tool, email header inspector, and internal threat knowledge wiki) to evaluate evidence artifacts.
4. The system shall trigger personal scam scenarios on a virtual personal smartphone interface during off-duty FSM states to evaluate player security decisions when personally targeted.
5. The system shall track persistent character trust metrics and update narrative storyline outcomes based on the accuracy and thoroughness of the player's ticket decisions.


## Non-functional requirements (how the system must PERFORM)
1. The system shall complete state transitions (such as switching between the Workstation desktop and the Personal Phone interface) within 0.5 seconds of user input.
2. The system shall maintain a rendering performance of at least 60 frames per second (FPS) on baseline target desktop hardware during active gameplay.
3. The system shall parse and load external scenario JSON data files into the FSM game logic within 2 seconds during initial application boot.
