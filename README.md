# iNatGPX
Convert iNaturalist observations csv file into gpx to import into GaiaGPS for offline use

App made with tasker
1. Go to <a href="https://www.google.com/url?q=https://www.inaturalist.org/observations/export">iNaturalist export</a>
 page<br>
2. Select place and taxon (preferably one state or smaller to not overload GaiaGPS with waypoints later)<br>
3. Set geoprivacy and taxon_geoprivacy to '<b>open</b>'<br>
Example query:<br><b> quality_grade=any&identifications=any&geoprivacy=open&taxon_geoprivacy=open&place_id=46&taxon_id=48703</b><br>

4. Enable these columns only:<br>
<b>-observed_on_string<br>-quality_grade<br>-url<br>-latitude<br>-longitude<br>-positional_accuracy<br>-scientific_name<br>-common_name<br>-taxon_id</b><br>
5. Export and download the zip file
6. Open iNatGPX app and choose months, merge files, and  coordinate precision limit
7. Click "Select zip file" and find the iNaturalist export zip file (do not manually extract the zip)
8. After zip file is automatically converted, click "Open GPX" and select the gpx file and open with GaiaGPS (do this each time for multiple gpx files)
<img width="1080" height="2100" alt="Screenshot_20260613_113342" src="https://github.com/user-attachments/assets/050e3a84-9fa2-4782-bd93-90e6f2a8ddc7" />
<img width="1080" height="2100" alt="Screenshot_20260613_113353" src="https://github.com/user-attachments/assets/8bff068e-d7d1-43e3-82df-0954cee72762" />
<img width="1080" height="2100" alt="Screenshot_20260613_113418" src="https://github.com/user-attachments/assets/1d89dd50-6db8-4790-9cc6-5f6a74e4139b" />
<img width="1080" height="2100" alt="Screenshot_20260613_121203" src="https://github.com/user-attachments/assets/4db9fab6-a0ab-4880-8a19-31ccce1348b0" />
<img width="1080" height="2100" alt="Screenshot_20260613_120913_Gaia GPS" src="https://github.com/user-attachments/assets/cbaa3951-3892-4777-b64e-e305eb610fe8" />
