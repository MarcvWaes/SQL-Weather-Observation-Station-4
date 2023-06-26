# SQL-Weather-Observation-Station-4

# Challenge:
- Find the difference between the total number of CITY entries in the table and the number of distinct CITY entries in the table.

- The STATION table is described as follows:

![n1e5uock jot](https://github.com/MarcvWaes/SQL-Weather-Observation-Station-3/assets/120553175/93033af8-77bd-460d-bf7b-fce39386b9e6)

- Where LAT_N is the northern latitude and LONG_W is the western longitude.

# Solution:
- SELECT COUNT(*) - COUNT(DISTINCT CITY) AS DIFFERENCE
- FROM STATION

# Output:
- 13
