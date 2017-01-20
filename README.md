# osmfilter

based on osmfilter by Markus Weber

added means to extract a particular ID

example:<br>
&nbsp;&nbsp;osmfilter planet.osm keep-id=9407
<br>
will extract all nodes, ways, and relationships
associated with the border of the country "Andorra"
(because id 9407 holds the border of Andorra in
the planet.osm).
