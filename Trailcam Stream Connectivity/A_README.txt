We have adopted and tweaked a low-cost methodology developed by Bellucci et al. 2020 to evaluate longitudinal stream connectivity using trail cameras. This method captures hourly images of a riffle-pool sequence which are rated on a categorical scale from 'dry' to 'flows above bankfull', and daily average ratings are used to generate a variety of metrics (e.g. mean duration of flows at a given category, frequency of days in or above a given category, average flow category across given time).

We adapted the approach to include an inferential test, which can allow statistical comparisons of (e.g.) a restored reach and a control or reference reach, with the intention that users can attribute observed change to their restoration actions when using a BACI (before-after-control-impact) study design. 

We have also include a parallel categorical rating system for application at nodes (confluences or bifurcations with off-channel or side-channel habitats).

Note that our adaptations are (as of spring 2025) untested with real field data. We intend to test them, but for now we provide some brief guidance and a document with data analysis code, so that restoration practitioners can begin collecting data.

><> ><> ><> ><> ><> ><> ><> ><> ><> <>< <>< <>< <>< <>< <>< <>< <><

The data analysis code script provided in this folder is adapted from the R source code and demo datasets shared by the authors of Bellucci et al. 2020 and available publicly here: https://github.com/marybecker/streamconnectivitymetrics. 

A very quick overview of the method:

	The General Field Method – 
o	Select a location on a stream that captures at least one riffle-pool sequence, or the node of interest 
o	Program the cameras to take one picture per hour and deploy them at the location(s) of interest
o	Visit the site to check the camera and battery, and download images from SD cards as needed

	Image Processing – 
o	Assign ratings to each hourly image based on a 6 category system developed to characterize stream connectivity
o	Calculate an average daily stream connectivity category based on the ratings assigned to each hourly image 
o	Calculate metrics to describe the magnitude, frequency, duration and timing components of stream connectivity

	Takeaways – 
o	Limited cost (~ USD 500 per deployment)
o	Time-efficient (a trained reader can process ~ 1000 pictures in one hour) 
o	Flexible – can be tailored to the research question/time period of interest
o	Can provide meaningful localised information on stream connectivity where information from gauges is absent
o	Provides quantitative metrics that can be compared visually or statistically between restored and control sites, and from before to after restoration.

><> ><> ><> ><> ><> ><> ><> ><> ><> <>< <>< <>< <>< <>< <>< <>< <><

Reference:

Bellucci, C.J., Becker, M.E., Czarnowski, M. and Fitting, C., 2020. A novel method to evaluate stream connectivity using trail cameras. River Research and Applications, 36(8), pp.1504-1514.