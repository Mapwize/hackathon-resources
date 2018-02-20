# Mapwize Hackathon Resources

Here are some basic resources to quickly hack on top of Mapwize's Indoor Mapping Platform.

## Get your Free Mapwize account.

To get your Mapwize account, sign up at [mapwize.io](https://www.mapwize.io).

You can create an API key to be able to use Mapwize API and SDK using Mapwize Studio.

If you need more capabilities than the Free Mapwize plan is offering, reach to the Mapwize team on site to get a free upgrade.

## Mapwize integration

If you need a simple map integration, mainly for wayfinding purposes, you could consider an iFrame / WebView integration of [maps.mapwize.io](https://maps.mapwize.io). Url parameters allow you to center the map on specific points at start-up, show directions and display user position.

If you want to code harder and deeper, then the Mapwize SDKs are made for you. They are available on iOS, Android and JS. The documentation can be found on [docs.mapwize.io](https://docs.mapwize.io) and sample apps are on [our Github page](https://github.com/mapwize). BTW, the code of the Mapwize app available on the iOS and Android stores is open-source.

## Indoor Location

The best way to add indoor location to your app and connect it to Mapwize maps is to use the open-source [Indoor Location framework](https://www.indoorlocation.io).

The framework provides a basic iBeacon positioning module that is easy to hack with, as well as connectors to many profesionnal indoor positioning solutions.

## Tips and trics

- Do not create a building map if you don't need to. Many public buildings are available on Mapwize and can be used. Moreover, existing public maps will often look nicer than what you could do in a few hours. Build a new map mainly if you need writing rights.
- Use the standard Mapwize apps on iOS, Android and the web to view your maps and debug. It's always better to make sure the map display properly before fighting with them in your app.