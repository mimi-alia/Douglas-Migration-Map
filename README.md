# Douglas-Migration-Map
A map that shows the migration of early-mid 20th century black students from various locations in America, chiefly Tennessee, to Elizabethton, Tennessee.
Layers:
  
  migration path(lines)
  
  the student's origin vs "current" residency via colored points
  
  homeowner status y/n (using the current residency points only) (loaded in code)

Interactive functions desired:
   
   legend w/ on/off toggle switch for those layers
   
   search bar so people can look up a specific resident if they want
    
   pop-ups over the points, so people can hover over a point and view all of the information stored in that individual's data log.
    
 The first two layers listed are already drawn in Mapbox Studio, and the third (homeowner status) has to be loaded through js I guess? I have been trying to add the data to the map throught the map.getLayer(), map.getStyle() functions to no avail.
