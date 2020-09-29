Comparing the Saturnus to a Caldwell G2

The Saturnus has alway been a great value proposition for the hobby as a general purpose chronograph for roughly half the cost of a cheap airsoft chrony and an order of magnitude cheaper than a ballistic chrony from companies like Caldwell. That said, I had been a little bit cautious about the accuracy, given the hand-assembled nature, hobbyist looking code, and lack of comparison to a known precise chrony like a Caldwell. I happened to be borrowing a Saturnus from a local when I got a Caldwell G2, so I decided to grab some data with both, and was very impressed when the Saturnus averaged within 3 fps of the Caldwell over 58 shots. I figured I'd release the data for future reference and to see if anyone else had similar (or different) experiences.

First, I should note that statistics is not a particular strength of mine; if I'm mis-applying a concept or overstating the significance of something, by all means, please correct me. I've also linked the data in a CSV at the bottom if you'd like to see the raw data for yourself.

**Methodology**
I used a Lynx (similar to a Talon Claw. It's still in beta; I'll post more numbers once it's released) with a 15.5" long 0.527" id Aluminum barrel and 8 kg Turf spring. The first 30 readings were done with a Thanhtacles Slurpee Scar, while the next 30 readings used no scar. I placed the Saturnus in between the sensors of the G2 so that it was just after the light bar of the first sensor (I really should have grabbed a picture of that while I still had the Saturnus on hand). I took the readings inside, so air currents should have had minimal effect.

For each set of readings, I loaded 15 fresh white Worker Gen 2s into a Talon, fired them, then collected them and fired them again for 30 readings total. A visual analysis of the graphs doesn't seem to suggest that using the darts a second time significantly impacted fps, though this is likely not enough data to fully draw that conclusion.

Each set of readings had one error on the Saturnus, which I also struck from the G2 readings to avoid skewing the stats. The reading for the Slurpee scar set was much lower and I think that the dart ricocheted off the Saturnus; the reading in the non-scar set is in line with the other results, so I suspect I didn't line it up properly over the Saturnus.

I used the Caldwell app to collect data from the G2, then exported the CSV from that. I collected the Saturnus data by reading it off the display and collecting it in a spreadsheet (this definitely could be a source of error).

**Data**
Across 29 data points for the Slurpee Scar data set, the Saturnus read an average of 165.1 fps, while the Caldwell G2 read an average of 168.3 fps, so the Caldwell read an average of 3.2 fps higher. The minimum fps the Saturnus read was 156 and the maximum was 173 for a spread for a spread of 17 fps, while the minimum the Caldwell read was 157 and the maximum was 173 for a spread of 16 fps.

For the non-scar data set, the Saturnus read an average of 175.0 fps, while the Caldwell read an average of 178.2 fps, so, again, the Caldwell read an average of 3.2 fps higher. The minimum fps the Saturnus read was 159 and the maximum was 183 for a spread for a spread of 24 fps, while the minimum the Caldwell read was 161 and the maximum was 185 for a spread of 24 fps.

It's quite reassuring that the averages and spreads are so close (they're little different if you take a higher precision), though it's not a consistent offset for every shot, as you can see in the following graphs. The slurpee scar set had a single reading where the Saturnus read higher than the Caldwell and two readings that matched the Caldwell, while the non-scar set had three readings higher than the Caldwell and one that matched the Caldwell.

Speaking of graphs, here they are:

These first two graphs show the fps of each reading, with the readings from the Saturnus in blue and the readings from the Caldwell in green. The holes in the graph are the errors that were struck from the data.

[Here's the Slurpee Scar readings](https://github.com/Daehder/DaehdersChronyData/blob/master/ComparingSaturnusAndCaldwellG2/SaturnusVsCaldwellG2SlurpeeScarReadings.png?raw=true)

[And the non-scar readings](https://github.com/Daehder/DaehdersChronyData/blob/master/ComparingSaturnusAndCaldwellG2/SaturnusVsCaldwellG2NoScarReadings.png?raw=true)

Both graphs are plotted on the exact same X and Y scale, so you can compare across the two graphs if you want to get a feel for how a Slurpee Scar impacts fps, though that is not the focus of this post (also, the raw data is linked below to make a closer comparison).

Both graphs have points with significant fps dips before and after the 15 dart mark (where I refilled the mag with the 15 darts I fired).
Some of this could be explained by bad darts (I'm not at the point where I'm examining every dart I fire, at least yet), but I don't know if that accounts for everything.
By my eye, the second half of the graph looks less stable, and we could see dart wear from being fired once reducing fps.
I'm not sure there's enough data to fully draw that conclusion, so I may need to revisit that in another post.

These next two graphs show the distribution of fps readings across both sets of 29 shots. Again, the Saturnus is in blue and the Caldwell in green

[Here's the Slurpee Scar FPS Distribution](https://github.com/Daehder/DaehdersChronyData/blob/master/ComparingSaturnusAndCaldwellG2/SaturnusVsCaldwellG2NoScarReadings.png?raw=true)

[And the non-scar distribution](https://github.com/Daehder/DaehdersChronyData/blob/master/ComparingSaturnusAndCaldwellG2/SaturnusVsCaldwellG2NoScarDistributions.png?raw=true)

The X-axes are both on the same scale, so the two graphs can be compared vertically, but the Y-axes are (slightly) different due to the different number of readings.
I can see the normal curves starting to form, but I'd definitely need more readings to get a proper curve and draw any strong conclusions.
That said, my spreadsheet is calculating a standard deviation of about 4 fps for the Slurpee Scar and between 5.75 and 5.49 fps for the non-scar, which seems to demonstrate some effect with the scar and show that the blaster is reasonably consistent.

[Oh, and here is the CSV with the raw data](https://github.com/Daehder/DaehdersChronyData/blob/master/ComparingSaturnusAndCaldwellG2/ComparingSaturnusAndCaldwellG2.csv)

**Conclusion**
Overall, I'm very impressed with the Saturnus. With an admittedly small sample size of a single unit, it's reading about 3 fps lower than a Caldwell G2 with a cost that is an order of magnitude lower than said Caldwell.

If you're looking for a cheap chrony to spot check your blaster before you take it to a game and dial it in over their chrony, it's a great option.

It does have some shortcomings though.
It's very sensitive to sunlight and various lighting conditions, so you'll definitely need to recalibrate it as lighting conditions change, and probably can't use it in direct sunlight (even behind a window).
It's also got a small reading area, so you've got to carefully aim your blaster over it; if you don't have a surface at a comfortable height to fire, you may find it kinda of awkward to hold the chrony in one hand, blaster in the other, and align the two.
Lastly, while this is fixable with software, there's no easy way to record fps readings into an easy to use format like a CSV.

So if you're looking for a chrony to rapidly fps-check a large group of people, I'd suggest a larger chrony like a Caldwell, especially for competitive play where accuracy is good for competitive integrity, and you've got someone else validating said accuracy.
Similarly, if you're looking to collect a large amount of fps data, and you don't want to develop your own data collection method, stick to something with an established data collection method.
