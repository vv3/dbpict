# A multi user photo album framework #

This is just an idea, no implementation exists yet.

All relevant photo metadata (including GPS coordinates, tagging, face
recognition etc) are extracted from the image files and injected into a
SQL database. Using the metadata one could build dynamic photo albums
"on-the-fly" simply by formulating a query. The query could contain
datetime restrictions, positional restrictions, camera-type restrictions

  Example: create a photo album named "Summer vacation 2017" using a
  query like "show all images taken with a CANON-EOS-XXX during the summer
  months of 2017"

  Example: create a photo album named "Summer vacation 2017 in Berlin"
  using a query like "show all images taken with a CANON-EOS-XXX having
  GPS positions within YY kilometeres from Berlin, during
  the summer months of 2017"

The application should contain some automatic machinery for detecting
new photos and injecting the metadata into the database. File uploads
via the app would be nice.

The web application shold probably integrate with some fancy Javascript
framework for doing the actual displaying and navigation of the selected
photos.

The web app could integrate with some Javascript library (Leaflet) for
displaying geographic maps indicating where photos are taken.

Some means of sharing photo albums among friends and family should be
supported (users, groups and access control).

