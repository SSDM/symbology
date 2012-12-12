Seafloor Survey Data Model - Symbology
====
The purpose of this symbology library is to provide a baseload of commonly used symbols which permits interoperability of spatial data between various software packages which need to consume and render SSDM based data in a consistent and reliable manner.   It should not be assumed this library is all encompassing.  It is a minimum set of common symbology codes and a corresponding graphical cartographic representation of that code.

The library consists of Point, Line and Fill symbols, which can be used to accruately render an Seafloor Survye Data Model.

The master graphics are managed and maintained as ESRI .style file, but the intention is to provide them for additional software products such as AutoCAD, Microstation and Starfix.

This repository provides reliable, easy and open access to the most current version of the SSDM Symbology library.  

<b>How it works...</b>
Within a SSDM geodatabase, a featureclass has an attribute called "SYMBOLOGY_CODE".  This attribute calue is mapped to the ESRI .style's 'Name' at rendering time.  Therefore all features in the SSDM with 'SYMBOLOGY_CODE= OGP1101' would be rendered with the symbol of name 'OGP1101'.


<html>
<body>
<table border='1'>
<th>ID</th>
<th>Category</th>
<th>Name</td>
<th>Symbol</th>
</th>
<tr>
<td>1</td>
<td></td>
<td>Fixed Point</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Fixed Point.png'</td>
</tr>
<tr>
<td>2</td>
<td></td>
<td>GWDepth</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GWDepth.png'</td>
</tr>
<tr>
<td>3</td>
<td></td>
<td>Box Core</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Box Core.png'</td>
</tr>
<tr>
<td>4</td>
<td></td>
<td>Existing Well</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Existing Well.png'</td>
</tr>
<tr>
<td>5</td>
<td></td>
<td>Gravity Core (3m)</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Gravity Core (3m).png'</td>
</tr>
<tr>
<td>6</td>
<td></td>
<td>Gravity Core (6m)</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Gravity Core (6m).png'</td>
</tr>
<tr>
<td>7</td>
<td></td>
<td>MooringLocations</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MooringLocations.png'</td>
</tr>
<tr>
<td>8</td>
<td></td>
<td>rock</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/rock.png'</td>
</tr>
<tr>
<td>9</td>
<td>BOEM</td>
<td>Side Scan Sonar Point</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Side Scan Sonar Point.png'</td>
</tr>
<tr>
<td>10</td>
<td>BOEM</td>
<td>Magnetic Anomaly (BOEM)</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Magnetic Anomaly (BOEM).png'</td>
</tr>
<tr>
<td>11</td>
<td>Buoy Mooring</td>
<td>EPA1505 SBM-Single Buoy Mooring</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1505 SBM-Single Buoy Mooring.png'</td>
</tr>
<tr>
<td>12</td>
<td>Environmental</td>
<td>OGP1201 Sound Velocity sample - SVP/TSdip</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1201 Sound Velocity sample - SVP_TSdip.png'</td>
</tr>
<tr>
<td>13</td>
<td>Environmental</td>
<td>EPA1304C Geochemical double successful</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1304C Geochemical double successful.png'</td>
</tr>
<tr>
<td>14</td>
<td>Environmental</td>
<td>EPA1304B Geochemical sample successful</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1304B Geochemical sample successful.png'</td>
</tr>
<tr>
<td>15</td>
<td>Environmental</td>
<td>EPA1304A Geochemical sample unsuccessful</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1304A Geochemical sample unsuccessful.png'</td>
</tr>
<tr>
<td>16</td>
<td>Environmental</td>
<td>EPA1304D Geochemical sample null</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1304D Geochemical sample null.png'</td>
</tr>
<tr>
<td>17</td>
<td>Environmental</td>
<td>EPA1304 Geochemical sample</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1304 Geochemical sample.png'</td>
</tr>
<tr>
<td>18</td>
<td>Environmental</td>
<td>EPA1301 Environmental Sampling - Water sample</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1301 Environmental Sampling - Water sample.png'</td>
</tr>
<tr>
<td>19</td>
<td>Environmental</td>
<td>EPA1302 Environmental Sampling - Benthic</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1302 Environmental Sampling - Benthic.png'</td>
</tr>
<tr>
<td>20</td>
<td>Environmental</td>
<td>EPA1303 Environmental Sampling - Sediment Profile Index (SPI)</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1303 Environmental Sampling - Sediment Profile Index (SPI).png'</td>
</tr>
<tr>
<td>21</td>
<td>Geophysical</td>
<td>EPA1152 Gravimeter</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1152 Gravimeter.png'</td>
</tr>
<tr>
<td>22</td>
<td>Geophysical</td>
<td>EPA1151 Maggy Point (Magnetometer)</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1151 Maggy Point (Magnetometer).png'</td>
</tr>
<tr>
<td>23</td>
<td>Geotechnical</td>
<td>OGP1101 Soil Sample</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1101 Soil Sample.png'</td>
</tr>
<tr>
<td>24</td>
<td>Geotechnical</td>
<td>OGP1102 Pilot Hole</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1102 Pilot Hole.png'</td>
</tr>
<tr>
<td>25</td>
<td>Geotechnical</td>
<td>OGP1103 Insitu Borehole</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1103 Insitu Borehole.png'</td>
</tr>
<tr>
<td>26</td>
<td>Geotechnical</td>
<td>OGP1104 Combi Borehole</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1104 Combi Borehole.png'</td>
</tr>
<tr>
<td>27</td>
<td>Geotechnical</td>
<td>EPA1101 Dropcore</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1101 Dropcore.png'</td>
</tr>
<tr>
<td>28</td>
<td>Geotechnical</td>
<td>EPA1107 Borehole</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1107 Borehole.png'</td>
</tr>
<tr>
<td>29</td>
<td>Geotechnical</td>
<td>EPA1106 Grab Sample</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1106 Grab Sample.png'</td>
</tr>
<tr>
<td>30</td>
<td>Geotechnical</td>
<td>EPA1102 Vibro Core</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1102 Vibro Core.png'</td>
</tr>
<tr>
<td>31</td>
<td>Geotechnical</td>
<td>EPA1103 CPT-Cone Penetration Test</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1103 CPT-Cone Penetration Test.png'</td>
</tr>
<tr>
<td>32</td>
<td>Geotechnical</td>
<td>EPA1104 PCPT-Piezo-cone Penetration Test</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1104 PCPT-Piezo-cone Penetration Test.png'</td>
</tr>
<tr>
<td>33</td>
<td>Geotechnical</td>
<td>EPA1105 Seismic PCPT-Piezo-cone Penetration Test</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1105 Seismic PCPT-Piezo-cone Penetration Test.png'</td>
</tr>
<tr>
<td>34</td>
<td>Infrastructure</td>
<td>EPA21105 Existing jacket</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA21105 Existing jacket.png'</td>
</tr>
<tr>
<td>35</td>
<td>Infrastructure</td>
<td>EPA21103 Platform</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA21103 Platform.png'</td>
</tr>
<tr>
<td>36</td>
<td>Oceanography Station</td>
<td>EPA1601 Tide Gauge</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1601 Tide Gauge.png'</td>
</tr>
<tr>
<td>37</td>
<td>Oceanography Station</td>
<td>EPA1603 Wave Scan</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1603 Wave Scan.png'</td>
</tr>
<tr>
<td>38</td>
<td>Oceanography Station</td>
<td>EPA1602 ADCP Acoustic Doppler Current Profilers </td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1602 ADCP Acoustic Doppler Current Profilers .png'</td>
</tr>
<tr>
<td>39</td>
<td>Seabed Feature Point</td>
<td>EPA1012 Proposed Well Location</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1012 Proposed Well Location.png'</td>
</tr>
<tr>
<td>40</td>
<td>Seabed Feature Point</td>
<td>EPA1009 Anchor Coordinates position</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1009 Anchor Coordinates position.png'</td>
</tr>
<tr>
<td>41</td>
<td>Seabed Feature Point</td>
<td>EPA32202 Spot Elevation</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA32202 Spot Elevation.png'</td>
</tr>
<tr>
<td>42</td>
<td>Seabed Feature Point</td>
<td>EPA1724 Shallow Gas</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA1724 Shallow Gas.png'</td>
</tr>
<tr>
<td>43</td>
<td>Seabed Feature Point</td>
<td>OGP1001 Coral Pinnacle</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1001 Coral Pinnacle.png'</td>
</tr>
<tr>
<td>44</td>
<td>Seabed Feature Point</td>
<td>OGP1002 Coral spotheight</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1002 Coral spotheight.png'</td>
</tr>
<tr>
<td>45</td>
<td>Seabed Feature Point</td>
<td>OGP1003 Seabed Mound</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1003 Seabed Mound.png'</td>
</tr>
<tr>
<td>46</td>
<td>Seabed Feature Point</td>
<td>OGP1004 Sonar Contact - High Backscatter</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1004 Sonar Contact - High Backscatter.png'</td>
</tr>
<tr>
<td>47</td>
<td>Seabed Feature Point</td>
<td>OGP1005 Isolated Depression or Pockmark</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1005 Isolated Depression or Pockmark.png'</td>
</tr>
<tr>
<td>48</td>
<td>Seabed Feature Point</td>
<td>OGP1006 Sonar Contact - Water Column</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1006 Sonar Contact - Water Column.png'</td>
</tr>
<tr>
<td>49</td>
<td>Seabed Feature Point</td>
<td>OGP1008 Shallow Gas</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1008 Shallow Gas.png'</td>
</tr>
<tr>
<td>50</td>
<td>Seabed Feature Point</td>
<td>OGP1021 Debris/Suspected Debris</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1021 Debris_Suspected Debris.png'</td>
</tr>
<tr>
<td>51</td>
<td>Seabed Feature Point</td>
<td>OGP1022 Wreck</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1022 Wreck.png'</td>
</tr>
<tr>
<td>52</td>
<td>Seabed Feature Point</td>
<td>OGP1023 Fish Trap</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1023 Fish Trap.png'</td>
</tr>
<tr>
<td>53</td>
<td>Seabed Feature Point</td>
<td>OGP1031 Post Drill Well</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP1031 Post Drill Well.png'</td>
</tr>
<tr>
<td>54</td>
<td>Seabed Feature Point</td>
<td>OGP32202 Spot Elevation</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP32202 Spot Elevation.png'</td>
</tr>
<tr>
<td>1</td>
<td>Bathymetry Contours</td>
<td>OGP3701 Major bathymetry contours</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3701 Major bathymetry contours.png'</td>
</tr>
<tr>
<td>2</td>
<td>Bathymetry Contours</td>
<td>OGP3702 Minor bathymetry contours</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3702 Minor bathymetry contours.png'</td>
</tr>
<tr>
<td>3</td>
<td>Bathymetry Contours</td>
<td>FGCI3701 Major structure contours</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/FGCI3701 Major structure contours.png'</td>
</tr>
<tr>
<td>4</td>
<td>Bathymetry Contours</td>
<td>FGCI3702 Minor structure contours</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/FGCI3702 Minor structure contours.png'</td>
</tr>
<tr>
<td>5</td>
<td>Infrastructure</td>
<td>EPA0267 Oil pipeline</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0267 Oil pipeline.png'</td>
</tr>
<tr>
<td>6</td>
<td>Infrastructure</td>
<td>EPA0266 Gas pipeline</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0266 Gas pipeline.png'</td>
</tr>
<tr>
<td>7</td>
<td>Infrastructure</td>
<td>EPA0268 Water Condensate Pipeline</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0268 Water Condensate Pipeline.png'</td>
</tr>
<tr>
<td>8</td>
<td>Infrastructure</td>
<td>EPA0269 Water Pipeline</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0269 Water Pipeline.png'</td>
</tr>
<tr>
<td>9</td>
<td>Infrastructure</td>
<td>EPA0283 Sub-marine cables</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0283 Sub-marine cables.png'</td>
</tr>
<tr>
<td>10</td>
<td>Infrastructure</td>
<td>EPA0292 Oil pipeline (Proposed)</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0292 Oil pipeline (Proposed).png'</td>
</tr>
<tr>
<td>11</td>
<td>Infrastructure</td>
<td>EPA0291 Gas pipeline (Proposed)</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0291 Gas pipeline (Proposed).png'</td>
</tr>
<tr>
<td>12</td>
<td>Infrastructure</td>
<td>EPA0295 Pipeline Span</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0295 Pipeline Span.png'</td>
</tr>
<tr>
<td>13</td>
<td>Infrastructure</td>
<td>EPA0284 Subsea cables</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0284 Subsea cables.png'</td>
</tr>
<tr>
<td>14</td>
<td>Infrastructure</td>
<td>EPA0297 Effluent Line</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0297 Effluent Line.png'</td>
</tr>
<tr>
<td>15</td>
<td>Infrastructure</td>
<td>EPA0298 Effluent Line (Proposed)</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0298 Effluent Line (Proposed).png'</td>
</tr>
<tr>
<td>16</td>
<td>Infrastructure</td>
<td>EPA0286 Subsea Cables (Proposed) </td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0286 Subsea Cables (Proposed) .png'</td>
</tr>
<tr>
<td>17</td>
<td>Infrastructure</td>
<td>EPA0299 Water Pipeline (Proposed)</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0299 Water Pipeline (Proposed).png'</td>
</tr>
<tr>
<td>18</td>
<td>Infrastructure</td>
<td>EPA0296 Abandoned Line (Oil, Gas)</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA0296 Abandoned Line (Oil, Gas).png'</td>
</tr>
<tr>
<td>19</td>
<td>Seabed Feature Line</td>
<td>OGP2001 Anchor scar/Plough mark</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2001 Anchor scar_Plough mark.png'</td>
</tr>
<tr>
<td>20</td>
<td>Seabed Feature Line</td>
<td>OGP2002 Linear debris</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2002 Linear debris.png'</td>
</tr>
<tr>
<td>21</td>
<td>Seabed Feature Line</td>
<td>OGP2005 Possible wreck</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2005 Possible wreck.png'</td>
</tr>
<tr>
<td>22</td>
<td>Seabed Feature Line</td>
<td>OGP2004 Trawl Scar</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2004 Trawl Scar.png'</td>
</tr>
<tr>
<td>23</td>
<td>Seabed Feature Line</td>
<td>OGP2003 Spud Can Drag Scar</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2003 Spud Can Drag Scar.png'</td>
</tr>
<tr>
<td>24</td>
<td>Shallow Geological Zone</td>
<td>OGP2112 Thrust Fault</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2112 Thrust Fault.png'</td>
</tr>
<tr>
<td>25</td>
<td>Shallow Geological Zone</td>
<td>OGP2055 Erosional/Mud Flow</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2055 Erosional_Mud Flow.png'</td>
</tr>
<tr>
<td>26</td>
<td>Shallow Geological Zone</td>
<td>OGP2059 Ridge</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2059 Ridge.png'</td>
</tr>
<tr>
<td>27</td>
<td>Shallow Geological Zone</td>
<td>OGP2051 Fault Scarp</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2051 Fault Scarp.png'</td>
</tr>
<tr>
<td>28</td>
<td>Shallow Geological Zone</td>
<td>OGP2121 Palaeo-Channel R1</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2121 Palaeo-Channel R1.png'</td>
</tr>
<tr>
<td>29</td>
<td>Shallow Geological Zone</td>
<td>OGP2111 Normal Fault</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2111 Normal Fault.png'</td>
</tr>
<tr>
<td>30</td>
<td>Shallow Geological Zone</td>
<td>OGP2201 Major Isopach Contours to base of Unit A</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2201 Major Isopach Contours to base of Unit A.png'</td>
</tr>
<tr>
<td>31</td>
<td>Shallow Geological Zone</td>
<td>OGP2202 Minor Isopach Contours to base of Unit A</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2202 Minor Isopach Contours to base of Unit A.png'</td>
</tr>
<tr>
<td>32</td>
<td>Survey Track</td>
<td>EPA2321 ROV Survey Track</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA2321 ROV Survey Track.png'</td>
</tr>
<tr>
<td>33</td>
<td>Survey Track</td>
<td>OGP2301 Navigation Track at Antenna Poisition</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2301 Navigation Track at Antenna Poisition.png'</td>
</tr>
<tr>
<td>34</td>
<td>Survey Track</td>
<td>OGP2302 Navigation Track at Boomer Position</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2302 Navigation Track at Boomer Position.png'</td>
</tr>
<tr>
<td>35</td>
<td>Survey Track</td>
<td>OGP2303 Navigation Track at CDP Poisition</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2303 Navigation Track at CDP Poisition.png'</td>
</tr>
<tr>
<td>36</td>
<td>Survey Track</td>
<td>OGP2304 Navigation Track at Echo-Sounder Poisition</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2304 Navigation Track at Echo-Sounder Poisition.png'</td>
</tr>
<tr>
<td>37</td>
<td>Survey Track</td>
<td>OGP2305 Navigation Track at Receiver Group Poisition</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2305 Navigation Track at Receiver Group Poisition.png'</td>
</tr>
<tr>
<td>38</td>
<td>Survey Track</td>
<td>OGP2306 Navigation Track at Pinger Poisition</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2306 Navigation Track at Pinger Poisition.png'</td>
</tr>
<tr>
<td>39</td>
<td>Survey Track</td>
<td>OGP2307 Navigation Track at Bin Centre Poisition</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2307 Navigation Track at Bin Centre Poisition.png'</td>
</tr>
<tr>
<td>40</td>
<td>Survey Track</td>
<td>OGP2308 Navigation Track at SSS Poisition/Centre of Source</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2308 Navigation Track at SSS Poisition_Centre of Source.png'</td>
</tr>
<tr>
<td>41</td>
<td>Survey Track</td>
<td>OGP2309 Navigation Track at Towfish/Tailbuoy Position</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2309 Navigation Track at Towfish_Tailbuoy Position.png'</td>
</tr>
<tr>
<td>42</td>
<td>Survey Track</td>
<td>OGP2310 Navigation Track at USBL Position</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2310 Navigation Track at USBL Position.png'</td>
</tr>
<tr>
<td>43</td>
<td>Survey Track</td>
<td>OGP2311 Navigation Track at Vessel Reference Point</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP2311 Navigation Track at Vessel Reference Point.png'</td>
</tr>
<tr>
<td>1</td>
<td>Hydrocarbon Fields and Prospect</td>
<td>2402 Oil field</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/2402 Oil field.png'</td>
</tr>
<tr>
<td>2</td>
<td>Hydrocarbon Fields and Prospect</td>
<td>2403 Gas field</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/2403 Gas field.png'</td>
</tr>
<tr>
<td>3</td>
<td>GINT</td>
<td>AC</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/AC.png'</td>
</tr>
<tr>
<td>4</td>
<td>GINT</td>
<td>AGG</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/AGG.png'</td>
</tr>
<tr>
<td>5</td>
<td>GINT</td>
<td>BASALT</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/BASALT.png'</td>
</tr>
<tr>
<td>6</td>
<td>GINT</td>
<td>BASALT-B</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/BASALT-B.png'</td>
</tr>
<tr>
<td>7</td>
<td>GINT</td>
<td>BASALT-F</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/BASALT-F.png'</td>
</tr>
<tr>
<td>8</td>
<td>GINT</td>
<td>BASALT-HW</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/BASALT-HW.png'</td>
</tr>
<tr>
<td>9</td>
<td>GINT</td>
<td>BASALT-O</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/BASALT-O.png'</td>
</tr>
<tr>
<td>10</td>
<td>GINT</td>
<td>BASALT-W</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/BASALT-W.png'</td>
</tr>
<tr>
<td>11</td>
<td>GINT</td>
<td>BASE</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/BASE.png'</td>
</tr>
<tr>
<td>12</td>
<td>Fugro West</td>
<td>BRECCIA</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/BRECCIA.png'</td>
</tr>
<tr>
<td>13</td>
<td>Fugro West</td>
<td>Carbonate</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Carbonate.png'</td>
</tr>
<tr>
<td>14</td>
<td>Fugro West</td>
<td>CH</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CH.png'</td>
</tr>
<tr>
<td>15</td>
<td>Fugro West</td>
<td>CHERT</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CHERT.png'</td>
</tr>
<tr>
<td>16</td>
<td>Fugro West</td>
<td>CH-G</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CH-G.png'</td>
</tr>
<tr>
<td>17</td>
<td>Fugro West</td>
<td>CHMH</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CHMH.png'</td>
</tr>
<tr>
<td>18</td>
<td>Fugro West</td>
<td>CH-S</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CH-S.png'</td>
</tr>
<tr>
<td>19</td>
<td>Fugro West</td>
<td>CH-WS</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CH-WS.png'</td>
</tr>
<tr>
<td>20</td>
<td>Fugro West</td>
<td>CL</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CL.png'</td>
</tr>
<tr>
<td>21</td>
<td>Fugro West</td>
<td>Clay</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Clay.png'</td>
</tr>
<tr>
<td>22</td>
<td>Fugro West</td>
<td>Clayey Sedimentary</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Clayey Sedimentary.png'</td>
</tr>
<tr>
<td>23</td>
<td>Fugro West</td>
<td>CLCH</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CLCH.png'</td>
</tr>
<tr>
<td>24</td>
<td>Fugro West</td>
<td>CL-G</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CL-G.png'</td>
</tr>
<tr>
<td>25</td>
<td>Fugro West</td>
<td>CLML</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CLML.png'</td>
</tr>
<tr>
<td>26</td>
<td>Fugro West</td>
<td>CLML-WS</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CLML-WS.png'</td>
</tr>
<tr>
<td>27</td>
<td>Fugro West</td>
<td>CL-S</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CL-S.png'</td>
</tr>
<tr>
<td>28</td>
<td>Fugro West</td>
<td>CL-S-G</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CL-S-G.png'</td>
</tr>
<tr>
<td>29</td>
<td>Fugro West</td>
<td>CL-WS</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CL-WS.png'</td>
</tr>
<tr>
<td>30</td>
<td>Fugro West</td>
<td>Coarse-Grained Sedimentary</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Coarse-Grained Sedimentary.png'</td>
</tr>
<tr>
<td>31</td>
<td>Fugro West</td>
<td>COBBLE</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/COBBLE.png'</td>
</tr>
<tr>
<td>32</td>
<td>Fugro West</td>
<td>CONCRETE</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CONCRETE.png'</td>
</tr>
<tr>
<td>33</td>
<td>Fugro West</td>
<td>CX</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/CX.png'</td>
</tr>
<tr>
<td>34</td>
<td>Fugro West</td>
<td>DX</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/DX.png'</td>
</tr>
<tr>
<td>35</td>
<td>Seabed Feature Polygon</td>
<td>EPA3019 Veneer of Soft Clay And/Or Exposure Underlying Stiff Sediments</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA3019 Veneer of Soft Clay And_Or Exposure Underlying Stiff Sediments.png'</td>
</tr>
<tr>
<td>36</td>
<td>Infrastructure</td>
<td>EPA3501 Platform</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA3501 Platform.png'</td>
</tr>
<tr>
<td>37</td>
<td>Infrastructure</td>
<td>EPA3502 Proposed/Planned Platform</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA3502 Proposed_Planned Platform.png'</td>
</tr>
<tr>
<td>38</td>
<td>Infrastructure</td>
<td>EPA3503 Proposed/Planned Jacket</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/EPA3503 Proposed_Planned Jacket.png'</td>
</tr>
<tr>
<td>39</td>
<td>Fugro West</td>
<td>FAULT-ZONE</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/FAULT-ZONE.png'</td>
</tr>
<tr>
<td>40</td>
<td>Fugro West</td>
<td>FILL</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/FILL.png'</td>
</tr>
<tr>
<td>41</td>
<td>Fugro West</td>
<td>GC</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GC.png'</td>
</tr>
<tr>
<td>42</td>
<td>Fugro West</td>
<td>GCCL</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GCCL.png'</td>
</tr>
<tr>
<td>43</td>
<td>Fugro West</td>
<td>GCGM</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GCGM.png'</td>
</tr>
<tr>
<td>44</td>
<td>Fugro West</td>
<td>GC-S</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GC-S.png'</td>
</tr>
<tr>
<td>45</td>
<td>Fugro West</td>
<td>GM</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GM.png'</td>
</tr>
<tr>
<td>46</td>
<td>Fugro West</td>
<td>GM-S</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GM-S.png'</td>
</tr>
<tr>
<td>47</td>
<td>Fugro West</td>
<td>GP</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GP.png'</td>
</tr>
<tr>
<td>48</td>
<td>Fugro West</td>
<td>GPGC</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GPGC.png'</td>
</tr>
<tr>
<td>49</td>
<td>Fugro West</td>
<td>GPGM</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GPGM.png'</td>
</tr>
<tr>
<td>50</td>
<td>Fugro West</td>
<td>GPGM-S</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GPGM-S.png'</td>
</tr>
<tr>
<td>51</td>
<td>Fugro West</td>
<td>GP-S</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GP-S.png'</td>
</tr>
<tr>
<td>52</td>
<td>Fugro West</td>
<td>GW</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GW.png'</td>
</tr>
<tr>
<td>53</td>
<td>Fugro West</td>
<td>GWGC</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GWGC.png'</td>
</tr>
<tr>
<td>54</td>
<td>Fugro West</td>
<td>GWGM</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GWGM.png'</td>
</tr>
<tr>
<td>55</td>
<td>Fugro West</td>
<td>GW-S</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GW-S.png'</td>
</tr>
<tr>
<td>56</td>
<td>Fugro West</td>
<td>GX</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GX.png'</td>
</tr>
<tr>
<td>57</td>
<td>Fugro West</td>
<td>GX-W</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/GX-W.png'</td>
</tr>
<tr>
<td>58</td>
<td>Fugro West</td>
<td>IG</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/IG.png'</td>
</tr>
<tr>
<td>59</td>
<td>Fugro West</td>
<td>Liquefaction</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Liquefaction.png'</td>
</tr>
<tr>
<td>60</td>
<td>Fugro West</td>
<td>LX</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/LX.png'</td>
</tr>
<tr>
<td>61</td>
<td>Fugro West</td>
<td>MARL</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MARL.png'</td>
</tr>
<tr>
<td>62</td>
<td>Fugro West</td>
<td>MARL-O</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MARL-O.png'</td>
</tr>
<tr>
<td>63</td>
<td>Fugro West</td>
<td>MARL-W</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MARL-W.png'</td>
</tr>
<tr>
<td>64</td>
<td>Fugro West</td>
<td>MET</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MET.png'</td>
</tr>
<tr>
<td>65</td>
<td>Fugro West</td>
<td>Metamorphic</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Metamorphic.png'</td>
</tr>
<tr>
<td>66</td>
<td>Fugro West</td>
<td>MH</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MH.png'</td>
</tr>
<tr>
<td>67</td>
<td>Fugro West</td>
<td>MH-S</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MH-S.png'</td>
</tr>
<tr>
<td>68</td>
<td>Fugro West</td>
<td>MH-WS</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MH-WS.png'</td>
</tr>
<tr>
<td>69</td>
<td>Fugro West</td>
<td>ML</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/ML.png'</td>
</tr>
<tr>
<td>70</td>
<td>Fugro West</td>
<td>MLCL</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MLCL.png'</td>
</tr>
<tr>
<td>71</td>
<td>Fugro West</td>
<td>ML-G</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/ML-G.png'</td>
</tr>
<tr>
<td>72</td>
<td>Fugro West</td>
<td>ML-S</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/ML-S.png'</td>
</tr>
<tr>
<td>73</td>
<td>Fugro West</td>
<td>ML-S-G</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/ML-S-G.png'</td>
</tr>
<tr>
<td>74</td>
<td>Fugro West</td>
<td>ML-WS</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/ML-WS.png'</td>
</tr>
<tr>
<td>75</td>
<td>Fugro West</td>
<td>MUDST</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MUDST.png'</td>
</tr>
<tr>
<td>76</td>
<td>Fugro West</td>
<td>MX</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MX.png'</td>
</tr>
<tr>
<td>77</td>
<td>Fugro West</td>
<td>MX-W</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/MX-W.png'</td>
</tr>
<tr>
<td>78</td>
<td>Seabed Feature Polygon</td>
<td>OGP3001 Isolated pockmark</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3001 Isolated pockmark.png'</td>
</tr>
<tr>
<td>79</td>
<td>Seabed Feature Polygon</td>
<td>OGP3002 Pockmark Cluster</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3002 Pockmark Cluster.png'</td>
</tr>
<tr>
<td>80</td>
<td>Seabed Feature Polygon</td>
<td>OGP3003 Coalesced/Combined Pockmark</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3003 Coalesced_Combined Pockmark.png'</td>
</tr>
<tr>
<td>81</td>
<td>Seabed Feature Polygon</td>
<td>OGP3004 Sand Ripples</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3004 Sand Ripples.png'</td>
</tr>
<tr>
<td>82</td>
<td>Seabed Feature Polygon</td>
<td>OGP3005 High Backscatter Sonar Area</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3005 High Backscatter Sonar Area.png'</td>
</tr>
<tr>
<td>83</td>
<td>Seabed Feature Polygon</td>
<td>OGP3006 Jack-up rig / Spudcan Footprint</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3006 Jack-up rig _ Spudcan Footprint.png'</td>
</tr>
<tr>
<td>84</td>
<td>Seabed Feature Polygon</td>
<td>OGP3007 Mound Cluster Area</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3007 Mound Cluster Area.png'</td>
</tr>
<tr>
<td>85</td>
<td>Seabed Feature Polygon</td>
<td>OGP3008 Pitted Area</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3008 Pitted Area.png'</td>
</tr>
<tr>
<td>86</td>
<td>Seabed Feature Polygon</td>
<td>OGP3009 Sonar/Hard Contact</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3009 Sonar_Hard Contact.png'</td>
</tr>
<tr>
<td>87</td>
<td>Seabed Feature Polygon</td>
<td>OGP3010 Coral Area</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3010 Coral Area.png'</td>
</tr>
<tr>
<td>88</td>
<td>Seabed Feature Polygon</td>
<td>OGP3021 Rock Dump</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3021 Rock Dump.png'</td>
</tr>
<tr>
<td>89</td>
<td>Seabed Feature Polygon</td>
<td>OGP3022 Soil Dump</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3022 Soil Dump.png'</td>
</tr>
<tr>
<td>90</td>
<td>Seabed Feature Polygon</td>
<td>OGP3023 Dredged Area - Trench</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3023 Dredged Area - Trench.png'</td>
</tr>
<tr>
<td>91</td>
<td>Seabed Feature Polygon</td>
<td>OGP3024 Dredged Area - Borrow</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3024 Dredged Area - Borrow.png'</td>
</tr>
<tr>
<td>92</td>
<td>Seabed Feature Polygon</td>
<td>OGP3025 Debris</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3025 Debris.png'</td>
</tr>
<tr>
<td>93</td>
<td>Seabed Feature Polygon</td>
<td>OGP3026 Disturbed Sediment Area</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3026 Disturbed Sediment Area.png'</td>
</tr>
<tr>
<td>94</td>
<td>Seabed Feature Polygon</td>
<td>OGP3027 Depression</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3027 Depression.png'</td>
</tr>
<tr>
<td>95</td>
<td>Seabed Feature Polygon</td>
<td>OGP3028 Mound - Mud/Mud Lumps</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3028 Mound - Mud_Mud Lumps.png'</td>
</tr>
<tr>
<td>96</td>
<td>Seabed Feature Polygon</td>
<td>OGP3029 Eroded/Thinned drape</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3029 Eroded_Thinned drape.png'</td>
</tr>
<tr>
<td>97</td>
<td>Seabed Feature Polygon</td>
<td>OGP3030 Shoal Area/Shallow Water Hazard</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3030 Shoal Area_Shallow Water Hazard.png'</td>
</tr>
<tr>
<td>98</td>
<td>Seabed Feature Polygon</td>
<td>OGP3031 Fish Traps</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3031 Fish Traps.png'</td>
</tr>
<tr>
<td>99</td>
<td>Sediment</td>
<td>OGP3101 Gravel</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3101 Gravel.png'</td>
</tr>
<tr>
<td>100</td>
<td>Sediment</td>
<td>OGP3102 Sand</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3102 Sand.png'</td>
</tr>
<tr>
<td>101</td>
<td>Sediment</td>
<td>OGP3103 Silt</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3103 Silt.png'</td>
</tr>
<tr>
<td>102</td>
<td>Sediment</td>
<td>OGP3104 Clay</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3104 Clay.png'</td>
</tr>
<tr>
<td>103</td>
<td>Sediment</td>
<td>OGP3201 Silty -Sand</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3201 Silty -Sand.png'</td>
</tr>
<tr>
<td>104</td>
<td>Sediment</td>
<td>OGP3202 Clayey-Sand</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3202 Clayey-Sand.png'</td>
</tr>
<tr>
<td>105</td>
<td>Sediment</td>
<td>OGP3203 Silty Clay</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3203 Silty Clay.png'</td>
</tr>
<tr>
<td>106</td>
<td>Sediment</td>
<td>OGP3204 Sandy-clay</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3204 Sandy-clay.png'</td>
</tr>
<tr>
<td>107</td>
<td>Sediment</td>
<td>OGP3205 Rocky</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3205 Rocky.png'</td>
</tr>
<tr>
<td>108</td>
<td>Survey Keysheet</td>
<td>OGP3301 Limit of Survey Area</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3301 Limit of Survey Area.png'</td>
</tr>
<tr>
<td>109</td>
<td>Survey Keysheet</td>
<td>OGP3302 Limit of Analogue and Digital Coverage</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3302 Limit of Analogue and Digital Coverage.png'</td>
</tr>
<tr>
<td>110</td>
<td>Survey Keysheet</td>
<td>OGP3303 Limit of Analogue Survey Coverage</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3303 Limit of Analogue Survey Coverage.png'</td>
</tr>
<tr>
<td>111</td>
<td>Survey Keysheet</td>
<td>OGP3304 Limit of Digital Survey Coverage</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3304 Limit of Digital Survey Coverage.png'</td>
</tr>
<tr>
<td>112</td>
<td>Shallow Geological Zone</td>
<td>OGP3701 Anomaly 1 High Amplitude</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3701 Anomaly 1 High Amplitude.png'</td>
</tr>
<tr>
<td>113</td>
<td>Shallow Geological Zone</td>
<td>OGP3702 Anomaly 2 High Amplitude</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3702 Anomaly 2 High Amplitude.png'</td>
</tr>
<tr>
<td>114</td>
<td>Shallow Geological Zone</td>
<td>OGP3703 Anomaly 3 High Amplitude</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3703 Anomaly 3 High Amplitude.png'</td>
</tr>
<tr>
<td>115</td>
<td>Shallow Geological Zone</td>
<td>OGP3704 Anomaly 4 High Amplitude</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3704 Anomaly 4 High Amplitude.png'</td>
</tr>
<tr>
<td>116</td>
<td>Shallow Geological Zone</td>
<td>OGP3705 Anomaly 5 High Amplitude</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3705 Anomaly 5 High Amplitude.png'</td>
</tr>
<tr>
<td>117</td>
<td>Shallow Geological Zone</td>
<td>OGP3706 Anomaly 6 High Amplitude</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3706 Anomaly 6 High Amplitude.png'</td>
</tr>
<tr>
<td>118</td>
<td>Shallow Geological Zone</td>
<td>OGP3707 Anomaly 7 High Amplitude</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3707 Anomaly 7 High Amplitude.png'</td>
</tr>
<tr>
<td>119</td>
<td>Shallow Geological Zone</td>
<td>OGP3708 Anomaly 8 High Amplitude</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3708 Anomaly 8 High Amplitude.png'</td>
</tr>
<tr>
<td>120</td>
<td>Shallow Geological Zone</td>
<td>OGP3709 Anomaly 9 High Amplitude</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3709 Anomaly 9 High Amplitude.png'</td>
</tr>
<tr>
<td>121</td>
<td>Shallow Geological Zone</td>
<td>OGP3710 Anomaly 10 High Amplitude</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3710 Anomaly 10 High Amplitude.png'</td>
</tr>
<tr>
<td>122</td>
<td>Shallow Geological Zone</td>
<td>OGP3721 Acoustic Blanking Zone</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3721 Acoustic Blanking Zone.png'</td>
</tr>
<tr>
<td>123</td>
<td>Shallow Geological Zone</td>
<td>OGP3722 Blanking Area</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3722 Blanking Area.png'</td>
</tr>
<tr>
<td>124</td>
<td>Shallow Geological Zone</td>
<td>OGP3723 Cross Bedding</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3723 Cross Bedding.png'</td>
</tr>
<tr>
<td>125</td>
<td>Shallow Geological Zone</td>
<td>OGP3724 Shallow Gas Zone</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OGP3724 Shallow Gas Zone.png'</td>
</tr>
<tr>
<td>126</td>
<td>Fugro West</td>
<td>OH</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OH.png'</td>
</tr>
<tr>
<td>127</td>
<td>Fugro West</td>
<td>OL</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/OL.png'</td>
</tr>
<tr>
<td>128</td>
<td>Fugro West</td>
<td>Organic/Asphalt/Igneous</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Organic_Asphalt_Igneous.png'</td>
</tr>
<tr>
<td>129</td>
<td>Fugro West</td>
<td>PEAT</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/PEAT.png'</td>
</tr>
<tr>
<td>130</td>
<td>Fugro West</td>
<td>PerfZone</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/PerfZone.png'</td>
</tr>
<tr>
<td>131</td>
<td>Fugro West</td>
<td>RF</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/RF.png'</td>
</tr>
<tr>
<td>132</td>
<td>Fugro West</td>
<td>Sand/Gravel</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Sand_Gravel.png'</td>
</tr>
<tr>
<td>133</td>
<td>Fugro West</td>
<td>SC</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SC.png'</td>
</tr>
<tr>
<td>134</td>
<td>Fugro West</td>
<td>SCCL</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SCCL.png'</td>
</tr>
<tr>
<td>135</td>
<td>Fugro West</td>
<td>SC-G</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SC-G.png'</td>
</tr>
<tr>
<td>136</td>
<td>Fugro West</td>
<td>SCSM</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SCSM.png'</td>
</tr>
<tr>
<td>137</td>
<td>Fugro West</td>
<td>SHALE</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SHALE.png'</td>
</tr>
<tr>
<td>138</td>
<td>Fugro West</td>
<td>SHALE-O</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SHALE-O.png'</td>
</tr>
<tr>
<td>139</td>
<td>Fugro West</td>
<td>SHALE-W</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SHALE-W.png'</td>
</tr>
<tr>
<td>140</td>
<td>Fugro West</td>
<td>Silt</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Silt.png'</td>
</tr>
<tr>
<td>141</td>
<td>Fugro West</td>
<td>Silty Sedimentary</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Silty Sedimentary.png'</td>
</tr>
<tr>
<td>142</td>
<td>Fugro West</td>
<td>SM</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SM.png'</td>
</tr>
<tr>
<td>143</td>
<td>Fugro West</td>
<td>SM-G</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SM-G.png'</td>
</tr>
<tr>
<td>144</td>
<td>Fugro West</td>
<td>SMML</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SMML.png'</td>
</tr>
<tr>
<td>145</td>
<td>Fugro West</td>
<td>SP</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SP.png'</td>
</tr>
<tr>
<td>146</td>
<td>Fugro West</td>
<td>SP-G</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SP-G.png'</td>
</tr>
<tr>
<td>147</td>
<td>Fugro West</td>
<td>SPSC</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SPSC.png'</td>
</tr>
<tr>
<td>148</td>
<td>Fugro West</td>
<td>SPSM</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SPSM.png'</td>
</tr>
<tr>
<td>149</td>
<td>Fugro West</td>
<td>SPSM-G</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SPSM-G.png'</td>
</tr>
<tr>
<td>150</td>
<td>Fugro West</td>
<td>SW</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SW.png'</td>
</tr>
<tr>
<td>151</td>
<td>Fugro West</td>
<td>SW-G</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SW-G.png'</td>
</tr>
<tr>
<td>152</td>
<td>Fugro West</td>
<td>SWSC</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SWSC.png'</td>
</tr>
<tr>
<td>153</td>
<td>Fugro West</td>
<td>SWSM</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SWSM.png'</td>
</tr>
<tr>
<td>154</td>
<td>Fugro West</td>
<td>SX</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SX.png'</td>
</tr>
<tr>
<td>155</td>
<td>Fugro West</td>
<td>SX-CAL</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SX-CAL.png'</td>
</tr>
<tr>
<td>156</td>
<td>Fugro West</td>
<td>SX-CON</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SX-CON.png'</td>
</tr>
<tr>
<td>157</td>
<td>Fugro West</td>
<td>SX-FOS</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SX-FOS.png'</td>
</tr>
<tr>
<td>158</td>
<td>Fugro West</td>
<td>SX-MX</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SX-MX.png'</td>
</tr>
<tr>
<td>159</td>
<td>Fugro West</td>
<td>SX-O</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SX-O.png'</td>
</tr>
<tr>
<td>160</td>
<td>Fugro West</td>
<td>SX-P</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SX-P.png'</td>
</tr>
<tr>
<td>161</td>
<td>Fugro West</td>
<td>SX-TUFF</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SX-TUFF.png'</td>
</tr>
<tr>
<td>162</td>
<td>Fugro West</td>
<td>SX-W</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SX-W.png'</td>
</tr>
<tr>
<td>163</td>
<td>Fugro West</td>
<td>SX-W-P</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/SX-W-P.png'</td>
</tr>
<tr>
<td>164</td>
<td>Fugro West</td>
<td>TUFF</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/TUFF.png'</td>
</tr>
<tr>
<td>165</td>
<td>Fugro West</td>
<td>TUFF-AGG</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/TUFF-AGG.png'</td>
</tr>
<tr>
<td>166</td>
<td>Fugro West</td>
<td>TUFF-O</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/TUFF-O.png'</td>
</tr>
<tr>
<td>167</td>
<td>Fugro West</td>
<td>TUFF-P</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/TUFF-P.png'</td>
</tr>
<tr>
<td>168</td>
<td>Fugro West</td>
<td>TUFF-W</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/TUFF-W.png'</td>
</tr>
<tr>
<td>169</td>
<td>Fugro West</td>
<td>Unknown</td>
<td><img src='https://github.com/SSDM/Symbology/raw/master/images/Unknown.png'</td>
</tr>
</table>
</body>
</html>
