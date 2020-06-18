# Crazy Taxi 

A modified Crazy Taxi game implemented with Verilog on the DE1-Soc Board. This project was collaborated with Angus Wang. Check out his Github profile [here!](https://github.com/angusYuhao)

## Rules 

In this game, the player controls the lane position of a taxi using the arrow keys to avoid incoming obstacles. There are two types of 
obstacles with different effects: 

1. Hitting a green truck decrements live count by 1
2. Hitting a banana stuns the player for 1 second, preventing the player from switching lanes

The game ends in victory if the player survives 30 rounds of incoming obstacles. The player starts with 2 lives. If the player loses both lives before 
30 rounds of obstacles, the player loses.

## How to Run This Game 

1. Create a new project on Quartus Prime
2. Include all .v files
3. Place all .mif files in current directory
4. Connect a DE1-Soc Board and a VGA display

Quartus Prime will program the DE1-Soc board and display the game on the
VGA display.

