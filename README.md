**Question**

  1. Create a Vehicle class that has the following fields: make, model, year, mileage, IsRunning, needsMaintnance, isTotalled
     
  2. the isTotalled is not something we decide upon creating an object. for every 4 vehicles we get 1 will be totalled
     
  3. The Vehicle class has the following methods: start and stop method that will turn the car on and off and sout which car is turned on or off
     
  4. displayInfo: should print the properties of the car in a way that makes sense
     
  5. Create a car class that inherits from the Vehicle class. This class should have the same fields and also include numberOfDoors and isElectric boolean
     
  6. displayInfo method should now display all the properties for the Car object
     
  7. create a checkForMaintenance method that will check if the car needs to be taken in for maintenance:
     a. If the car is electric then anything above 100,000 km needs maintenance
     b. If the car is gas powered tha  anything above 125,000 km needs maintenance
