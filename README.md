# MadHatter
A Local Escape room startup asked for help with creating a cake puzzle.
Basically the player will find clues around the room and these should lead them to blowing out the candles on the cake in a certain order to move on.
This project uses 4 WS2812B addressible LEDS, 4 condensder mic elements and 4 modified shock sensors.
The sensor spring was removed and the MIC installed (observe polarity). 
When the player blows on the candle the mic picks up the sound of the blowing and triggers an event via shock sensor. 
Basically weve just switched the spring sensor element to a piezo element.
