<h1># Lunite</h1>
<h2>A life support reporter that reports on key life support things, like oxygen, water, and food. It tells how long it can sustain the mission with the amount of each that you provide. It calculates water, oxygen, energy use & return, and food.</h2>

<h2>Demo:</h2>
https://vrramroop.github.io/Lunite/

<h3>Overview: By inputting the present supply levels and use rates, a time estimation of how long each resource will last will be given. For the weakest (least) resource, there is a live counter to show how long you have.</h3>


<h3> Information: To ensure the code works properly, please ensure that you input the following parameters: </h3>
  1. Colonists: Total number of mission staff
  2. Water (Liters): Total water (not including water for water)
  3. Oxygen (Kg): O2 reserves
  4. Energy (kWh): Current use / gain (solar panels etc)
  5. Food (KG): Dehydrated sustenance <br>
<strong>WRITE NUMBERS ONLY</strong>


<h3>Notes:</h3>
Entering 0 for any resource puts the Emergency line. 
The calculator adds 2L of water per person rate to the standard 5L rate to account for hydrating the dehydrated food, making it 7L in total.
There are some inconsistencies with the upload times for the index.html and the v2, thats because I was rushing to ship the project to the challenger sidequest.
Energy estimates will either be Infinity or 0. The infinity comes from if the gain exceeds or equals the need, and 0 comes from if the need exceeds the gain.


<h3>Total Fixed Rates:</h3>
Oxygen: 0.84 kg
Water: 7.0 Liters (5L Drinking + 2L Food Rehydration)
Food: 1.0 kg (Dehydrated)



<i>
Background image 1 of moon credit - https://plus.nasa.gov/video/moon-101-the-lunar-surface/
Background image 2 of moon credit - https://svs.gsfc.nasa.gov/13537/
</i>
