#Geocode ... ? ... Anyone? geocodeAnyone!

##WHAT?

A deadly simple JavaScript library to deal with the geocode API.


##Requisites

	typeof google.maps.Geocoder != "undefined"


##HOW

Include the google code 
	<script src="http://maps.google.com/maps/api/js?sensor=true"></script>

Get the geolocation data using an input string:

	geocodeAnyone.getAddressFromAddress("your address string",callback);

Or ask to the client to enable the geolocation API:

	geocodeAnyone.askAddress(callback);



##SHUT UP! GIVE ME A COMPLETE EXAMPLE

Open examples/index.html