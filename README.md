# Lamport Logical Clock Simulator

## Project Description
The Lamport Logical Clock Simulator is a Java-based mini project that demonstrates event ordering in distributed systems using logical clocks.

## Objectives
- Understand Lamport's Logical Clock algorithm.
- Assign timestamps to events.
- Demonstrate message communication between processes.
- Maintain logical ordering of events.

## Technologies Used
- **Programming Language:** Java
- **Platform:** VS Code / IntelliJ IDEA
- **Concept:** Distributed Computing

## Algorithm
1. Initialize all process clocks to zero.
2. Increment the clock for every event.
3. Attach the timestamp when sending a message.
4. Update the receiver's clock using `max(local clock, received timestamp) + 1`.
5. Display the updated timestamps.

## How to Run
1. Install Java JDK.
2. Create a file named `LamportClock.java`.
3. Copy the project code into the file.
4. Compile the program:

   `javac LamportClock.java`

5. Run the program:

   `java LamportClock`

## Expected Output
```text
P1 Event: 1
P1 sends message: 2
P2 receives message: 3
P2 Event: 4
P2 sends message: 5
P3 receives message: 6
P3 Event: 7
```

## Conclusion
This project successfully demonstrates Lamport's Logical Clock algorithm and explains how event ordering is maintained in distributed systems.

## Author
**Lakshmipriya V A**
