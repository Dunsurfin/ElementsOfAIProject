<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Catch The Next El to Work

This is the final project for the Building AI course from <a href="https://www.elementsofai.com/">Elements of AI</a>. Please note that this is an idea for a project and not a finished solution.

## Summary

Currently, the Chicago Transport Authority (CTA) runs trains every 15 minutes on the Brown Line during my commute to work in the morning and home in the evening. This integration would remind me the optimal time to leave to catch the next train.


## Background

Chicago has pretty extreme weather – deadly cold in the depths of winter and deadly hot in the heights of summer. Standing on a train platform waiting for the next train is not always fun, particularly as many stations are open to the elements with limited shelters.

This integration calculates the average walking time from home and work to the nearest El station, and then suggests optimal times to leave to catch the next train.


## How is it used?

Ideally, this integration works as a reminder on a smartwatch on time to leave. The user would want to run the app to indicate that they are almost ready to commute (although this element could be automated based upon calendar and geofencing data). The app would reference the average time that the user takes to get to the station (based upon individual training data over a couple of weeks) and check against the CTA’s train tracker data to suggest optimal time to leave. 


## Data sources and AI methods
The CTA’s open data is published here: https://www.transitchicago.com/data/
Location data from the smartwatch would be shared with the app (with user’s permission)
Nearest El station data would be stored as a favorite by the user, with the option to alter if at different home or work location. When searching for a new nearest station, the app would reference an internal database of options.


## Challenges

Usability is probably the greatest challenge. The data sources and methods are already employed by disparate applications (for example Google Maps), but are not integrated into a friendly application that does not require more active involvement by the user.

## What next?

I don’t have the skills to code this yet, but I am going to dig deeper into how this might happen.


## Acknowledgments
