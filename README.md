# LOCATING THE MALLS NEAR ME
You can easily track my daily schedule or moves, one of the things in the loop is visiting the mall. I
came into Iowa State just about a month ago, one of the few things I wanted to check out or know
about is where the credible malls to get necessities are located. My flat mate introduced me to
Walmart, it is pretty far, my thought was that, it is the only credible mall here. Later on, I realized
there are host of other malls. That may be a good thing to dive into for this case study, knowing all
the malls near me. So I used the API from the google earth and used that to extract the malls
within a particular radius near me.

## Retrieving your API

One of the major step into achieving this is creating your API from this website
https://console.cloud.google.com/ (https://console.cloud.google.com/) , after you have done that,
you may need to activate it by creating a suitable project and add an API, add your IP address
where necessary, it may also need your billing account, include your card details, the service is
completely free, so nothing should happen to the liquid in your bank account, however, if you still
feel insecure, remove your card details when you are done with the project.

## Choosing your coordinate, keyword and radius

Your location would determine the coordinate, you will work with.Choose the coordinates, you want
to work with, pick a suitable one and, assign a keyword as well, in my case, it is the ‘mall’, choose
a suitable radius.

## Documentation

The documentation would really help you in extracting the right format for extracting the url and the
api call. Here is the website https://developers.google.com/maps/documentation/
(https://developers.google.com/maps/documentation/) Check out the documentations, use this website to get the details of your place, geocoding and there valuable examples in there to guide you. From the documentation, you will know how to get the right url, The request would help extract the
details in the url, the json would load them in as text.

## Printing the location of the malls

You will need to assign a variable to each of the key containing the values. The ones we are using
is the name, place_id, lat, lng, rating, types and vicinity.
Google earth doesn't allow you to scrape more than 20 places per page, but updated the
documentation which allows you se the next page token but still would not exceed 60 places.

## Visualizing the points on the open street map

You can visualize the location of the malls on the open street map using mapbox, assigning the
latitude and longitude based on what is available on the data generated.

## Exporting to excel
After you have gotten the list of the mall that are available, what you can do, is to export them to
the excel so that they are well documented

## Conclusion

One of the challenge is with picking shorter radius, it didn't allow since there are limited data for
that, from the list of 60 malls after extending the radius, there are places located in Des_Moine in
the list, infact, those in Ames is just about one-third of the list

