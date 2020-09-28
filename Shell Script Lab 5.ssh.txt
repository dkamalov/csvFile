//Imports Chicago Public Servant information file and sorts by salary

curl -o ChicagoPublic.csv https://data.cityofchicago.org/api/views/xzkq-xp2w/rows.csv?accessType=DOWNLOAD&bom=true&format=true
sort -k 7 ChicagoPublic.csv