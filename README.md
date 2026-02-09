instructions on usage of the functions

gyro straight: the first value is the distance to go. the second is speed% and third is if you want to turn during movement(it will always fix to the wanted degree. even if a previous turn was wrong)

gyro turn: first value is the degree to turn to the second is a speed multiplier and the third is by how many degrees is it allowed to miss(it will be fixed later) and if the turn is to a degree higher than 180 then first reset yaw angle and variable 1

gyro color: same as gyro straight but instead of time its what color to stop at. (0 is black)
