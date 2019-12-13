# Capstone_starting
Its my first Capstone_Project to understand the essence of applied data science based on the real life problem and their Solutions.
<!-- wp:heading {"level":3,"customTextColor":"#f20408"} -->
<h3 class="has-text-color" style="color:#f20408"><strong>Business Problem:</strong></h3>
<!-- /wp:heading -->

<!-- wp:list -->
<ul><li>After world war migration pattern changes and after that most people choose north America and European countries as new home. UK is one of the countries for migration and its data are available from UK government official report.</li><li>Our stakeholder wants to know the special pattern or facility trend among the migrators and new buyer for purchase in London.</li><li>Main motto is to see the data insights of the data to increase business decisions and profit margin for real state investment.</li></ul>
<!-- /wp:list -->

<!-- wp:heading {"level":3,"customTextColor":"#f20408"} -->
<h3 class="has-text-color" style="color:#f20408"><strong>Data Collection and Understanding</strong></h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Here, we need to gather the data from the online available certified public data for the migration pattern, House buying scenario, Area codes &amp; map data and postal codes.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>For that we will use following data set.</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>HM Land registry Home price paid data (Country: UK)</li><li>Google Map Geocoding (Google Map data to represent the pattern on map (heat map))</li><li>Foursquare Location Data</li></ul>
<!-- /wp:list -->

<!-- wp:heading {"level":3,"customTextColor":"#f20408"} -->
<h3 class="has-text-color" style="color:#f20408"><strong>Tools</strong></h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Data hosting platform (IBM cloud, IBM cognitive LAB ovenware)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>Data Processing</strong></p>
<!-- /wp:paragraph -->

<!-- wp:group {"backgroundColor":"pale-cyan-blue"} -->
<div class="wp-block-group has-pale-cyan-blue-background-color has-background"><div class="wp-block-group__inner-container"><!-- wp:heading {"level":4,"textColor":"vivid-red"} -->
<h4 class="has-vivid-red-color has-text-color"><strong>Stage 1</strong></h4>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Import data ( Use IBM DB2 import function)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Give column Name for understanding and unique ideal formatting and better merging.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Change date format to standard python standard</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Filter data after 2016 and sort in ascending order.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Filter London city data and arrange them to street wise panda format</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Merge data of street and price to get average price of houses for particulars streets.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Use Google Map (geocoding data) for latitude and longitude of streets.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Grouping latitude, longitude, street names and average prices for map presentation using folium.</p>
<!-- /wp:paragraph --></div></div>
<!-- /wp:group -->

<!-- wp:group {"backgroundColor":"pale-cyan-blue"} -->
<div class="wp-block-group has-pale-cyan-blue-background-color has-background"><div class="wp-block-group__inner-container"><!-- wp:heading {"level":4,"textColor":"vivid-red"} -->
<h4 class="has-vivid-red-color has-text-color"><strong>Stage 2</strong></h4>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Use Foursquare data set and format them to client id, client secret, version, latitude, longitude, radius and limitation of area)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Format structure of venues list and convert it to panda data frame format with name nearby venue.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Our standard format must be:</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Street Name | Street Latitude| Street Longitude |Venue| Venue Latitude |Venue Longitude | Venue Category</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Separate location venue from nearby Venue data frame.</p>
<!-- /wp:paragraph --></div></div>
<!-- /wp:group -->

<!-- wp:group {"backgroundColor":"pale-cyan-blue"} -->
<div class="wp-block-group has-pale-cyan-blue-background-color has-background"><div class="wp-block-group__inner-container"><!-- wp:heading {"level":4,"textColor":"vivid-red"} -->
<h4 class="has-vivid-red-color has-text-color"><strong>Stage 3</strong></h4>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Create nearby facility data with radius of 5 km surrounding data from foursquare API.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Give them same formatting as same as nearby venue function.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Get location facility from getnearby facility&nbsp; with street , latitude and longitude information.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Now for analysis grouping street wise and get count for each facility</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The facilities are grocery store, supermarket, elementary schools, High schools, Hospitals.</p>
<!-- /wp:paragraph --></div></div>
<!-- /wp:group -->

<!-- wp:heading {"customTextColor":"#f20408"} -->
<h2 class="has-text-color" style="color:#f20408"><strong>Conclusion:</strong></h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>People buy house near to facilized areas and average price for them are higher than other street areas.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Most preferable faculties are Hospital, Elementary schools.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3,"customTextColor":"#f20408"} -->
<h3 class="has-text-color" style="color:#f20408"><strong>Attachments:</strong></h3>
<!-- /wp:heading -->

<!-- wp:heading {"level":4} -->
<h4><strong><a href="https://github.com/vedantdave77/PROJECT--UK_Price-Prediction_Capstone/blob/master/Coursera_Capstone_UK_Price_Index_VD_Python_Code.ipynb">Code File</a></strong></h4>
<!-- /wp:heading -->

<!-- wp:heading {"level":4} -->
<h4><a href="https://github.com/vedantdave77/PROJECT--UK_Price-Prediction_Capstone/blob/master/Coursera_Capstone_UK_Price_Index_VD_Data.pdf">Business Problem Report</a></h4>
<!-- /wp:heading -->

<!-- wp:heading {"level":4} -->
<h4><a href="https://github.com/vedantdave77/PROJECT--UK_Price-Prediction_Capstone/blob/master/Coursera_Capstone_UK_Price_Index_VD_Business_Probelm.pdf"><strong>Opensource public data information </strong>Data</a></h4>
<!-- /wp:heading -->

<!-- wp:heading {"level":4} -->
<h4><strong><a href="https://github.com/vedantdave77/PROJECT--UK_Price-Prediction_Capstone/blob/master/Coursera_Capstone_UK_Price_Index_VD_Final_Report.pdf">Final Report</a></strong></h4>
<!-- /wp:heading -->

<!-- wp:heading {"level":4} -->
<h4><a href="https://github.com/vedantdave77/PROJECT--UK_Price-Prediction_Capstone/blob/master/Coursera_Capstone_UK_Price_Index_VD_Presentation.pdf">Presentation</a></h4>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p></p>
<!-- /wp:paragraph -->
