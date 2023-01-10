---
course: MTRN3100
year: 2023 T2
---

# Competition Specification

---

## Scenario

This project consists of 2 milestones:

1. Closed-Loop Driving: Is the robot able to drive autonomously and stay centre between two walls?
1. Maze Solving: Is the robot able to drive autonomously to explore a maze then solve it in the quickest time possible?

The robot begins a maze-solving run by being placed in the start zone and is ready to receive a transmission.

The maze-solving run timer starts when the robot has been transmitted the coordinates of the start and end zone.

The maze-solving run timer ends when the robot has reached the end zone and the robot successfully transmits that the robot has stopped.

### Robot Requirements

The robot requirements is as follows:

- Robot dimensions must always be within $x \times y \times z$.
- The robot may only use wheeled locomotion and may not fly, jump, climb, walk, etc.
- The robot must move autonomously with any human input for the entire duration of a maze-solving run.
- The robot may only use 1D LiDAR or ultrasonic sensors for wall perception.
- The robot must 
- The robot must be powered by a battery fixed to the robot and untethered to any stationary power source (e.g. wall sockets, off-board batteries, etc.).
- The robot must be controlled by a controller fixed to the robot and untethered to any stationary computer source (e.g. laptops, PCs, off-board microcontrollers, etc.).
- Components must be sourced from the [approved robot kit](#kit).
- Software libraries must be sourced from [approved libraries](#libraries).

> Permission must be sought for unapproved components and libraries. This is so consistency and fairness is maintained for the competition.

Your team may:

- Create their own chassis with any wheel and electrical device configuration.
- Write their own libraries provided they are not copied from any 3rd party libraries.

### Arena

- Maze base dimensions are $x \times y$.
- The walls of the maze are plywood panels of dimensions $x \times y \times z$.
- The floor of the maze is sheet vinyl.
- The start zone is identified by a green taped area.
- The end zone is identified by a red taped area.
- There are multiple possible paths from the start zone to the end zone.
- The maze configuration will change with each lab session.

### Teams

- Your team must be formed with students from your designated lab slot.
- Team sizes are between $4 - 6$ with the ideal team size being $5$. If a team does not have between $4 - 6$ members, then team reshuffling may occur.
- Issues within the team (e.g. conflict, absentism) must be reported immediately to your designated lab demonstrator.

---

## Kit

Your team is provided at no cost exactly the following list of components:
- $1 \times$
- $2 \times$

If your team has damaged any component and require a replacement, then the replacement must come out of the team's personal budget.

Your team may use any combination of the kit for milestones 1, 2, and 3 as long as the specification is adhered to.

---

## Libraries

Your team may only use any of the following 3rd party libraries:

---

## Milstone 1 - Platform

The robot is checked to see if it meets the competition specification. Robots which do not pass all of the robot requirements will not be permitted to progress to milestone 2 and 3 until the requirements are all passing.

### Marking Criteria

This is an all-or-nothing mark where all of the robot requirements must be met.

---

## Milestone 2 - Closed-Loop Driving

The objective of this milestone is to validate that the robot can autonomously drive in the maze according to a transmitted drive plan. A higher level controller capable of closed-loop driving i.e. the position and/or velocity of the robot is updated using the distance sensors.

### Marking Criteria

This milestone is checked during Week 7 in your allocated exam block (timetabled as OTH) at Willis Annexe 215. The expected deliverables of this milestone are:

- A drive plan (i.e. a sequence of random coordinates) must be successfully read by the robot from an incoming bluetooth transmission on __ protocol. <div style="color:red">[1 mark]</div>
- The robot must successfully execute the drive plan and is considered to have arrived at a coordinate when it is within a marked zone. If the drive plan could not be transmitted in, then the team may hardcode the coordinates. <div style="color:red">[0.5 marks for each action, 4 marks, 8 actions]</div>
- The robot must accurately drive along the centreline between adjacent walls. <div style="color:red">[0.25 marks for each action, 2 marks in total, 8 actions]</div>
- Your code will be evaluated for good software design practices i.e.:
    - Use of files, namespaces, and classes to create a loosely-coupled software stack. <div style="color:red">[1 mark]</div>
    - Readable code with clear logic, sensible comments, indentation, and spacing. <div style="color:red">[0.5 mark]</div>
    - Sensible names for files, variables, classes, and/or functions. <div style="color:red">[0.5 mark]</div>

### Submission

Submission of your code is done by pushing the latest code version to your **review** branch by 23:55 ___. 

### Team Evaluation

An individual evaluation of your team must be submitted by 23:55 ___ otherwise equal contribution will be assumed.

---

## Milestone 3 - Maze Solving

### Marking Criteria

### Submission

### Team Evaluation

---

## Prize

The prize is the learning and friends we made along the way.

---

## Forum Expectations

---

## Plagiarism Warning

Don't do it. Offenses of plagiarism will warrant a zero for the milestone assessment, with more serious cases warranting zero for the course.
