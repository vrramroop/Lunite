# Lunite
A life support reporter that reports on key life support things, like oxygen, water, and food. It tells how long it can sustain the mission with the amount of each that you provide. It calculates water, oxygen, energy use & return, and food.


Overview: By inputting the present supply levels and use rates, a time estimation of how long each resource will last will be given. For the weakest (least) resource, there is a live counter to show how long you have. 


Information: To ensure the code works properly, please ensure that you input the following parameters:
  1. Colonists: Total number of mission staff
  2. Water (Liters): Total water (not including water for water)
  3. Oxygen (Kg): O2 reserves
  4. Energy (kWh): Current use / gain (solar panels etc)
  5. Food (KG): Dehydrated sustenance


Notes:
Entering 0 for any resource puts the Emergency line. 
The calculator adds 2L of water per person rate to the standard 5L rate to account for hydrating the dehydrated food, making it 7L in total.


Total Fixed Rates:
Oxygen: 0.84 kg
Water: 7.0 Liters (5L Drinking + 2L Food Rehydration)
Food: 1.0 kg (Dehydrated)



Background image 1 of moon credit - https://plus.nasa.gov/video/moon-101-the-lunar-surface/
Background image 2 of moon credit - https://svs.gsfc.nasa.gov/13537/
