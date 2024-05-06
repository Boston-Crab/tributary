# Tributary
Forage Ford workday simulation


Tributary is the backbone of Ford's sensor streaming setup. It's built with Flask and stores data in a Redis database. It has two main parts: one that gets data from sensors in vehicles (using the /record endpoint), and another that serves that data to a mobile app (using the /collect endpoint). So, sensors in the car send data to the server, and then users can access that data through their phones.
