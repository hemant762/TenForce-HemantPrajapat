In the current provided solution, we are calculating the sum of all the moons gravity simultaneously while assigning the moon to the ICollection<Moon>.
We can also iterate over ICollection<Moon> (after assigning all the moons to it) one by one and get the sum of the gravity of all the moons.
But it will increase the time complexity by O(N), where N is the number of moons on a planet.
So I decided to choose the solution, which is calculating the sum of all the moon's gravity simultaneously while assigning the moon to the ICollection<Moon> Aka current provided solution.