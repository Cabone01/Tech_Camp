# Weather API
Using the Openweather api I was able to obtain data on over 500 randomly selected cities. Several scatter plots were made using the cities by latitiude, max temperature, 
humidity, and wind speed. Something I noticed is that there are appears to be a sort of bell curve in the city latitude vs. max temp graph. It is not particularly 
clean but from both directions they rise in max temperature as they reach latitiude at around 10. Another thing that I think is worth noting is that for cities in 
both southern and northen hemispheres, there is basically no difference in wind speed. The difference of r value for both is so small that I can say that the 
hemisphere a city is in does not have a correlation with wind speed. This could also be seen be the linear regression plot made in both as it is very close to just being 
a straight horizontal line. The last thing of note is cloudiness of a city based on its hemishpere. Looking at the northern hemisphere graph, we can see that linear 
regression plotted is nearly horizontal meaning that there is little to no correlation between the two. Oddly enough though looking at the souther hemisphere, 
the linear regression plot shows that there is a negative correlation between the two. However, the r value is a mere -0.15 which is really weak correlation. This 
leads me to still believe that there is not really any connection between the hemishpere and wind speed.
