library("leaflet")
leaflet() %>% addTiles() %>% setView(77.668889, 12.922822, 6) %>%
  addMarkers(
    lat = 13.039306 , lng = 80.261925,
    label = "Chennai: Place of Birth",
    labelOptions = labelOptions(noHide = T)) %>%
  addMarkers(
    lat = 12.922822, lng = 77.668889,
    label = "Bengaluru: Place of Residence",
    labelOptions = labelOptions(noHide = T)) %>%
  addMarkers(
    lat = 13.352459, lng = 74.792693,
    label = "Manipal Institute of Technology: My college",
    labelOptions = labelOptions(noHide = T)) 
