# Google-maps

This is a research and practice on the Google Map API

JS
###OPTION 1
<script>
var map;
function initMap(){
  var mapCanvas = document.getElementById('map');
  var mapOptions = {
    center: new.google.maps.LatLng(-34.397,150.644 );
    zoom:8;
    mapTypeId: google.maps.MapTypeId.ROADMAP
  }
  
  ####execution
  google.maps.event.addDomListener('window', load, initMap);
}
</script>


###//OPTION 2
function initMap() {
                map = new google.maps.Map(document.getElementById('map'), {
                   center: {lat: -34.397, lng: 150.644},
                     zoom: 8
                  });
    }
    
    <script src="https://maps.googleapis.com/maps/api/js?key=KEY&callback=initMap"
        async defer></script>
    
    
