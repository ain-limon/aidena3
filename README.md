Requirements Analysis:
Simulate an elevator in a multi-story building.
Input parameters:
    1) Number of floors.
    2) Maximum passengers per trip.
    3) Simulation duration in minutes.
Output parameters:
    1) Total time taken by the elevator.
    2) Call frequency per floor.
    
Class Structure Design:
`Elevator`:
    1) Represents the elevator itself.
    2) Stores current floor, maximum passengers, total time, request queue, and call frequency.
Methods:
        1) `callElevator()`: Adds a call request.
        2) `processRequests()`: Processes the request queue.
        3) `moveToFloor()`: Moves the elevator to the target floor.
        4) `unloadPassengers()`: Simulates unloading passengers.
        5) `displayStatistics()`: Displays elevator statistics.
`Simulation`:
    1) Manages the simulation.
    2) Stores simulation parameters (number of floors, maximum passengers, duration), elevator object, and an array to track call frequency.
 Methods:
        1) `startSimulation()`: Starts the simulation.
        2) `generateRandomCalls()`: Generates random elevator calls.
        3) `trackFloorCalls()`: Tracks and updates floor call frequency.
