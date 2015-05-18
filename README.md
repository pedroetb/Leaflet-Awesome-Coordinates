# Leaflet-Awesome-Coordinates
This is a very simple [Leaflet](https://github.com/Leaflet/Leaflet) map example using my own fork of [Leaflet-Coordinates](https://github.com/pedroetb/Leaflet.Coordinates) with [Leaflet.awesome-markers](https://github.com/lvoogdt/Leaflet.awesome-markers).

I made this example to show the potential use of new features added in my fork of *Leaflet-Coordinates*, allowing users to customize the overexploited Leaflet's default marker.
It's tested with [Leaflet.awesome-markers](https://github.com/lvoogdt/Leaflet.awesome-markers), but you can test it with any other marker types and/or properties if you wish (maybe only changing the icon image url, for instance).

## Screenshot
![Leaflet-Awesome-Coordinates screenshot](https://raw.github.com/pedroetb/Leaflet-Awesome-Coordinates/master/images/Leaflet-Awesome-Coordinates.png "Leaflet-Awesome-Coordinates screenshot")

## Setup

### Prerequisites
If not installed yet, you need to install [node.js](https://nodejs.org/) to use **npm**.

Of course, you need **git** to get this project and its submodules.

### Getting submodules
The project includes a filled *.gitmodules* file, you only have to initialize and update submodules.
```
# after git clone of Leaflet-Awesome-Coordinates
cd Leaflet-Awesome-Coordinates
git submodule init
git submodule update
```

### Building submodules
The only submodule which need to be built is Leaflet. The rest of submodules also includes the built resources, so you don't need to do nothing to them.
```
cd Leaflet-Awesome-Coordinates/submodules/Leaflet
npm install
```

## Using the example
Open the index.html into your web browser and type some visible coordinates. You will see the custom marker added in map.
