# [NYC-Hotspot-Locator](https://jbrereton.com/CSAEA/NYC-Hotspot-Locator/)
---

The NYC Hotspot locator is a simple JavaScript app with UI designed in Code.org App Lab. I used the Code.org ["NYC Public Wifi Locations" dataset](NYC%20Public%20Wifi%20Locations.csv) which contains about 2,500 entries and sufficent information for each location. The application uses the user entered latitude and longitude to calculate the distance between the user and each Wi-Fi hotspot in the dataset. This data is then sorted into an ordered list and displayed for the user, unfortunately list sorting in JavaScript is very inneficient especially with large data sets, resulting in a 2 to 4 minute wait.
