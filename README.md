A robot factory's test facility needs a Robot Simulator program to verify Robot movements. You have a test suite for both the robot interface and the simulator the robot factory hopes to use. Your job is to implement both the robot's navigational code, along with the simulator used to test the robot.
Use meaningful commit messages and try to timebox yourself to 90 min. When we pair, we will be adding additional functionality.

The robot only has three possible movements:
turn right
turn left
advance

In the simulation, robots are placed on a hypothetical infinite grid, facing a particular direction (north, east, south, or west) at a set of {x,y} coordinates, e.g., {3,8}, with coordinates increasing to the north and east.

The robot then receives a number of instructions, at which point the testing facility verifies the robot's new position, and in which direction it is pointing.

The letter-string "RAALAL" means:
Turn right
Advance twice
Turn left
Advance once
Turn left yet again

In the above example, a robot starting at {7, 3} facing north would end at {9, 4} facing west.