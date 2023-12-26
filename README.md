# Weather-App-Java
The Weather App is a Java-based tool that shows users the current weather for a chosen place. It gets this info from an outside source and presents it in a simple app you can see on your computer. You type in where you want to know the weather, and the app shows you details like temperature, weather description, humidity, and wind speed. This guide explains how the project is set up, the tech it uses, and what each part of the app does.

# Tech Used:
Java 18
JSON Simple: This helps read and understand information in JSON format.
HTTPURLConnection: A built-in tool in Java for getting data from other websites, helping us fetch info from outside sources.

# Class Overviews:
1. AppLauncher
   
What it does: Start up the Weather App when you open it.

3. WeatherAppGui
   
What it does: Makes the Weather App look good on your screen, showing the weather for your chosen place.
Summary: This part manages how the app looks, including where you type the location and where the weather details show up. It listens to what you type and updates the weather when you ask.

4. WeatherApp
   
What it does: Gets the weather data from an outside source, turns it into something readable, and ensures the app shows the right info.
Summary: This part is like the brain of the Weather App. It knows how to ask for weather details and where to show them. It ensures everything works smoothly between what you see and the info it gets from outside.

Feel free to ask if you want more details or have questions!
