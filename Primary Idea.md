# Cloud based smart surveillance 

## How is this smart
Multi actor identity recogniser(neural net) + Activity mapper(neural net) + Threat assesment(neural net). It can identify multiple actors in the scene + what activity each actor is doing.
Have a default threat level for each actor. Terrorists + People with prior criminal backgrounds
Raise threat levels through a combination of user's threat level

## Components
* Actor database: Have a databse of actors. Actors all have bayesian threat levels as well as any other useful info. Don't know if we need support for non human actors.
* Identity Recogniser: The identity recogniser tells the most likely match in the actor databse.
* Activity Mapper: The activity mapper tells you the activity going on from a dataset of activites. Each activity has a threat level. For eg combat is a high threat activity.
* Miscellaneous Event Recogniser: Recognize events like fire which don't have an actor. This needs to be improved upon.

## Applications
* Activity threat coupled with Actor history allows you to predict criminal 
* Detect key events like fighting, fire, tresspassing,  
* Government city wide surveillance.
* Airport threat assesment by comparison with existing terrorist databases.
* Bank threat assesment.

## ThinkList
* Write this like a research paper.

* Have to compare with existing approaches.
* Find out which companies use cctv control rooms. Should be a good application.
* Add a unique identifier for each object detected like man#34591, dog#91231  https://www.youtube.com/watch?v=aG7V7_zowZU

* If the identity mapper can further map identities
* Discuss this idea with profs etc.
* Does our actor recognizer work even in the night with infrared cameras?
* Turn on lights etc in the area, sound alarms
* Allow collecting with

# Potential Issues
* How easy is the criminal database to find? Might be tougher in a country like India. How frequently is it updated?
* Will the intelligence layer be on the cloud or each individual webcam.

# Competitor
* Smart cctv https://smartcctvfrs.wordpress.com/2015/03/06/your-face-becomes-a-barcode-algorithmic-surveillance/
* https://www.youtube.com/watch?v=aG7V7_zowZU

# Existing Approaches

# How this is better