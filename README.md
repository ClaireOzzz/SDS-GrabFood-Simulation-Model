# Systems-Design-Studio-2023

npm cache clean --force  (run only if there are errors after npm i)

npm install

npm install @turf/turf

npm install @turf/helpers

npm install --save geojson-path-finder

npm install gsap

npm install --save random-normal 

npm install plotly.js  

npm install react-plotly.js@2.2.0     

export NODE_OPTIONS=--max-old-space-size=4096       //when u get that fatal error

npm start

layer for routes was extracted using:
https://mygeodata.cloud/osm/data/download/


User index:
Location: (road coordinate not actual)
state: complete/waiting/unassigned


"start": "react-scripts --max_old_space_size=4096 start",
"build": "react-scripts --max_old_space_size=4096 build"

FIXME:
2. Reset button bug (when journey ends)
3. Reset button bug (when clicked twice)
4. Dashboard resize bug
5. Input waiting time, change to minutes

TODO: 
1. Driver moves onto next customer after first job is done
2, Output 2: occupied to unoccupied driver
3. Output 3: Customers served by hour (len of elapsed time array)
4. Dynamic graphs for statsbar

3. Option to export data as json/CSV on statsbar
4. Dashboard: checkbox for path viewing
5. Dashboard: checkbox for icons/points
6. Run 30 times in backend
9. Add food waiting time range bar
10. Make the statsbar slide out when click instead of hover


DASHBOARD LAYOUT
AGENTS:
- Driver Number
- Customer Number
- Food waiting time (set range)

VARIABLES:
- Weather
- Type of Transport
- Time of Day

SETTINGS:
- Speed
- Checkbox: show intended driver paths
- Checkbox: show icons, or points
- Number of runs (changing it to >1 will cause the statbar to slide out)