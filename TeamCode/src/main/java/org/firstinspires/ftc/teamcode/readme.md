10/16
We worked on the PID loop for the code. PID stands for Proportionality, Integration and Differential
using these powerful concepts of mathematics to control our motors.
    We accumulate the error generated. We calculate this by defining an actual position and asking the encoders
    in the motor for the positoion. desired_position - actual_position = error.
    We also have a multiplication factor that we use to control the speed of the arm by controlling the