# getStatesAndCountries
This class is defined to retrieve all the states and countries and also the states related to any particular country.

Two methods are defined in this class:
1. Map<String, String> getCountryAndStatesMap(String name, String dep)
This method will return a map.
If the name is "country" then a list of all coutries will be returned.
If the name is "state" then a list of all states will be returned.
If the name is "" then a null will be returned.

If the dep is "name" then a map will have country/state name - country/state code
if the dep is "code" then a map will have country/state code - country/state name
If dep is "" then null will be returned.

2. Map<String,String> getStatesForSelectedCountry(String country, String dep)
This method will return a map.

The country should contain the complete name of the country, if the country is not accurate then null will be returned.

If the dep is "name" then a map will have state name - state code which is related to any particular country.
if the dep is "code" then a map will have state code - state name which is reltaed to any particular country.
If dep is "" then null will be returned.
