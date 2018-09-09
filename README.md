# PureGeocoder

A Geocoder that will work by scraping OpenStreetMap. 

Documentation: https://hexdocs.pm/pure_geocoder/api-reference.html

## Getting Started
+ `$ git clone https://github.com/jackHedaya/pure_geocoder`
+ `$ cd pure_geocoder`
+ `$ mix deps.get`

## Installation
Add dependency to `mix.exs` file:

`defp deps do 
   [{:pure_geocoder, "~> 0.1.0"}] 
end`

### Dependencies
+ <a href="https://github.com/devinus/poison">Poison</a>
+ <a href="https://github.com/edgurgel/httpoison">HTTPoison</a>
