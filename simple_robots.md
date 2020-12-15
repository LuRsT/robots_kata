# Asteroid Robots

## About this task

Try to use [TDD](https://en.wikipedia.org/wiki/Test-driven_development) to solve this exercise.

## About the robot

A robot position is represented by a pair of co-ordinates and the robot’s current bearing.
An example position might be (1, 3, South) which means that the robot is 1 mile east and three miles north and is facing south.

The co-ordinate of the position one place North from (0,0) is (0, 1).

## Controlling the robot

The robot can be given three instructions:
- Move forward: The robot will move one coordinate in the direction of it's bearing
- Turn left: The robot will turn to the left, changing it's rotation to the left of the current one (example: From North to West)
- Turn right: The robot will turn to the right, changing it's rotation to the right of the current one (example: From North to East)



```
    North
West  .  East
    South
```


## Assumptions

- For the purposes of this exercise there are no limits to where the robot can go.

## Your Code

You should be able to have an object which represents the robot, its location and bearing,
and also methods allowing it to move around according to the rules above.
