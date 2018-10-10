# Magnetic fields in heavy ion collisions using MCGlauber as a position generator
  We implement a code to evaluate the magnetic field in heavy ion collision using the free code MCGlauber, which is downloadable in this page: https://github.com/MCGlauber/. The MCGlauber is used to generate the positions of every proton inside the nuclei on each simulation. The Lienard-Wichert equation is used to calculate the magnetic field with the consideration that the velocity of each proton is the same and is constant. 
 
We discriminate the protons in 3 types, the first one we consider all the protons without the protons nearest to the origin, the condition is if the protons are nearer than 0.3fm. We do not consider them to calculate the magnetic field event by event.
The other type we only consider the participants protons, these are the protons that at least collisionate with one proton of the other nuclei. Then we make the same discrimination as the first type.  The third type we consider the protons
In fact the code calculate the magnetic fields of three types of spectators protons, these are the protons that not collisionate without any proton of the other nuclei.And apply the same distance from the origin discrimination.

At last, the code generate some plots of the magnetic field as function of the impact parameter.





