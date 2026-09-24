GENERAL INFORMATION

1. Title of Dataset:
Replication data for: Data-driven transfer functions from differential magnetometer measurements to enhance GIC model validation capability: A case study in the Spanish power grid

2. Author information:

Santiago Marsal Vinadé
C.\ Observatori, 3-A
43520 Roquetes
Tarragona (Spain)
smarsal@obsebre.es

Joan Miquel Torta Margalef
C.\ Observatori, 3-A
43520 Roquetes
Tarragona (Spain)
jmtorta@obsebre.es

Juan José Curto Subirats
C.\ Observatori, 3-A
43520 Roquetes
Tarragona (Spain)
jjcurto@obsebre.es

Òscar Cid Solé
C.\ Observatori, 3-A
43520 Roquetes
Tarragona (Spain)
ocid@obsebre.es

Miquel Ibañez Caballé
C.\ Observatori, 3-A
43520 Roquetes
Tarragona (Spain)
mibanez@obsebre.es

3. Date of data collection:
Selected dates in the range 2020-06-01 - 2024-08-31.

4. Geographic location of data collection <latitude, longiute, or city/region, State, Country, as appropriate>: 
Spain

5. Information about funding sources that supported the collection of the data:
Projects PID2020-113135RB-C32 and PID2020-113135RB-C31 funded by Ministerio de Ciencia e Innovación.

SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data:
CC-BY-SA

2. Links to publications that cite or use the data: 
Marsal, S., Torta, J. M., Martí, A., Hafizi, R., Piña-Varas P., Marcuello, A., Ledo, J., Curto, J. J., Queralt, P., Cid, O., Ibañez, M. (2025). Data-driven transfer functions from differential magnetometer measurements to enhance GIC model validation capability: A case study in the Spanish power grid. Space Weather journal.

3. Was data derived from another source?
No

4. Recommended citation for this dataset: 
Marsal, S., Torta, J. M., Martí, A., Hafizi, R., Piña-Varas P., Marcuello, A., Ledo, J., Curto, J. J., Queralt, P., Cid, O., Ibañez, M. (2024). Replication data for: Data-driven transfer functions from differential magnetometer measurements to enhance GIC model validation capability: A case study in the Spanish power grid. CORA repository.

DATA & FILE OVERVIEW

1. File List: 
250 ASCII data files (plain text) containing mainly magnetic data associated with the Differential Magnetometer Method (DMM) aimed at deriving the Geomagnetically Induced Current (GIC) flowing in power transmission lines.
Readme.txt	File specifying the structure of the files containing the data	5,5 kB	Text	

2. Are there multiple versions of the dataset?
No

METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 
See, e.g.:
- Marsal, S., Torta, J. M., Martí, A., Hafizi, R., Piña-Varas P., Marcuello, A., Ledo, J., Curto, J. J., Queralt, P., Cid, O., Ibañez, M. (2025). Data-driven transfer functions from differential magnetometer measurements to enhance GIC model validation capability: A case study in the Spanish power grid. Space Weather journal.
- Marsal, S., Torta, J. M., Curto, J. J., Canillas-Pérez, V., Cid, O., Ibañez, M., Marcuello, A. (2021). Validating GIC modeling in the Spanish power transmission grid by differential magnetometry. Space Weather journal. https://doi.org/10.1029/2021SW002905
- Matandirotya, E., Cilliers, P.J., Van Zyl, R.R., Oyedokun, D.T., & Villiers, J. de. (2016). Differential magnetometer method applied to measurement of geomagnetically induced currents in Southern African power networks. Space Weather. https://doi.org/10.1002/2015SW001289
- Hübert, J., Beggan, C.D., Richardson, G.S., Martyn, T., & Thomson, A.W.P. (2020). Differential Magnetometer Measurements of Geomagnetically Induced Currents in a Complex High Voltage Network. Space Weather, 18(4), e2019SW002421. https://doi.org/https://doi.org/10.1029/2019SW002421

2. Methods for processing the data: 
The data have not been processed.

3. Instrument- or software-specific information needed to interpret the data: 
Plain text editor.

4. Standards and calibration information, if appropriate: 
Instrumentation: LEMI-044 magnetometers.

5. People involved with sample collection, processing, analysis and/or submission: 
The authors of this dataset.

DATA-SPECIFIC INFORMATION:

All files have the same structure:

Fragment of data:  
1    2  3  4  5  6   7        8         9          10     11      12  13    14         15 16         17 18 19 20 21
2019 09 03 11 16 36  -960.862 21377.979 44408.582  29.58  11.99   63  342.5 4947.93364 N 02400.54580 E 12 2 1 1
2019 09 03 11 16 37  -962.984 21380.096 44408.640  29.58  11.99   63  342.6 4947.93369 N 02400.54572 E 12 2 1 1
2019 09 03 11 16 38  -963.473 21380.264 44406.820  29.58  11.99   63  342.9 4947.93373 N 02400.54564 E 12 2 1 1
2019 09 03 11 16 39  -965.165 21379.486 44407.246  29.58  11.99   63  343.1 4947.93375 N 02400.54555 E 12 2 1 1
2019 09 03 11 16 40  -966.535 21380.467 44407.125  29.58  11.99   64  343.3 4947.93381 N 02400.54546 E 12 2 1 1


#	Data		description	Notes
1	2019		Year	
2	09		Month	
3	03		Day	
4	11		Hour	
5	16		Minute	
6	36		Second	
7	-960.862	Bx		nT
8	21377.979	By		nT
9	44408.582  	Bz		nT
10	29.58		TE		ºC
11	11.99		Power supply	V
12	63	Current consumption	mA
13	342.5		altitude		meter
14	4947.93364	Latitude	
15	N		Hemisphere	
16	02400.54580	Longitude	
17	E		Hemisphere	
18	12		Satellites number	
19	2		GPS binding time	
20	1		Deviation from the PPS, +/-127*	
21	1		PLL readiness (can be 0 - PLL is not ready or 1 - PLL is ready)	
*Note: to calculate deviation from PPS in nanosecond this number has to be multiplied by 61.

1. Number of variables: 
21

2. Number of cases/rows: 
One per second

3. Variable List: 
See above.

4. Missing data codes: 
N/A
