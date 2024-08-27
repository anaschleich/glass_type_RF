# Glass Classfication
Create a simple Random Forest Classifier to predict the glass type, based on a dataset of glass metrics. 

The dataset features different glass metrics, a mix of physics and chemistry properties to understand and predict what type of glass they refer to.

## The properties include:
1. Refractive Index (RI) of the glass, which is an optical property
2. Chemical elements such as: 
   - Na: Sodium (unit measurement: weight percent in corresponding oxide, as are attributes 4-10)
   - Mg: Magnesium
   - Al: Aluminum
   - Si: Silicon
   - K: Potassium
   - Ca: Calcium
   - Ba: Barium
   - Fe: Iron
3. Type of glass (glass attribute):
-- 1 building_windows_float_processed
-- 2 building_windows_non_float_processed
-- 3 vehicle_windows_float_processed
-- 4 vehicle_windows_non_float_processed (none in this database)
-- 5 containers
-- 6 tableware
-- 7 headlamps

Based on those, we should be able to predict the type of glass they correspond to: tableware, headlamps, etc.
