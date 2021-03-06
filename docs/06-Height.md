# Height  

Forest height can be measured in multiple different ways. The metrics below detail the differnt measures used to assess forest height.



## Canopy relief ratio ($CRR$) {-}  

A measure of the relative shape of the canopy from lidar or altimetry. Also known as the elevation relief ratio ($ERR$).

$$CRR = \frac{h_{mean} - h_{min}}{h_{max} - h_{max}}$$

Reference:  
[Parker and Russ, 2004](https://doi.org/10.1016/j.foreco.2003.09.001)


## Maximum canopy height ($H_{max}$) {-}  

Maximum canopy height is the maximum measured canopy height value in meters (m).  


## Mean height ($\overline{H}$) {-}  

Mean height, also mean canopy height or $H$, is a lidar derived metric measuring
the mean return height of all lidar pulses in some $X,Y$ defined coordinate space,
and defined spatial resolution. For TLS and UAV based sensors this resolution is often 1 m, 
while for ALS is typically 10 to 30 m. 

See also:  
[$p50$](### Percentile heights (e.g. $p10$, $p25$, $p50$))  

Reference:  
[Atkins et al. 2018](https://doi.org/10.1111/2041-210X.13061)


## Mean outer canopy height {$MOCH$} {-}  

$MOCH$ is the mean or average height of the outer canopy ($Z_m$) of a forest based on 
some resolution, $X$ or $X,Y$. For example, for aerial lidar scanning or ALS, $MOCH$
can be calculated from a canopy height model (CHM) as the mean value of each $Z$ over a
defined $X,Y$ coordinate space or as the mean of all values in that CHM. For terrestrial lidar (TLS), 
$MOCH$ is often defined as the average of the highest lidar return (also defined as $Z_max$) 
for each $X$ or $X,Y$ coordinate space with a standard resolution of 1 m. 

See also:  

[Maximum canopy height ($H_{max}$)](## Maximum canopy height ($H_{max}$))  

Reference:  
[Atkins et al. 2018](https://doi.org/10.1111/2041-210X.13061)



## Median height ($\tilde{H}$) {-}  

Median height $\tilde{H}$ is a lidar derived metric measuring
the median return height of all lidar pulses in some $X,Y$ defined coordinate space,
and defined spatial resolution. For TLS and UAV based sensors this resolution is often 1 m, 
while for ALS is typically 10 to 30 m. 



## Percentile heights (e.g. $p10$, $p25$, $p50$) {-}  
 
Percentile heights, or height percentiles, measure the vertical distribution of 
plant area or plant volume density and are most typically derived from lidar data. 
Percentile heights are in units of meters (m) and represent the height of the $i^{th}$ percentile. 
For example, a $p50$ value of 10.25 m indicated that 50% of the plant area or volume in that vertical
column of forest occurs below that height threshold, while 50% occurs below. Similarly, 
a $p25$ of 3.45 m would indicate 25% of the plant area or volume is below 3.45 m, with the remaining 75% above. 
$p50$ is approximately equal to the mean canopy height $H$ (see [Mean height ($H$)](### Mean height ($H$)))  

See also:  
[Quantile calculation](https://en.wikipedia.org/wiki/Quantile)



## Relative heights (e.g. $RH10$, $RH25$, $RH50$) {-}  

Relative height values are measures of lidar return energy rather than "direct" measures of height, indicating the height in meters (m) where the $ith$ percentile of energy is remaining. Relative height values are derived most typically from air- or spaceborne waveform lidar. They are approximately equal to percentile heights (see [Percentile heights](### Percentile heights (e.g. $p10$, $p25$, $p50$)))  

## Top Rugosity $R_T$ {-}  

Top rugosity, $R_T$ is defined as the standard deviation of 

