# FireFightingAndMazeSolver
Arduino Code for Fire Fighting Along With a Maze following robot
The robot follows a maze i.e. avoids obstcales on its path using an Ultrasonic sensor until it finds a glowing candle or some fire on its way. It then moves towards the candle by means of Infrared sensors and pours water on it so as to extinguish the candle. 
The "maze_solver" is the arduino code for Obstacle avoidance.
The "maze_solver_using_1_IR" is the combination of obstacle avoidance and fire extinguisher using 1 infrared sesnsor mounted on a servo motor which detects fire on all sides by rotating 180 degrees on encountering an obstacle.
The "maze_solver_using_3_IR" uses 3 infrared sensors to detect the fire . The three sensors are mounted on chassis at the front , right and left and one ultrasonic sensor for obstacle detection.
The "fire_fighting_using_3_IR" is simply the code for a candle blowing robot using water as a fire extinguising agent.
