---
layout: default
---

<figure>
	<iframe width="100%" height="365px" src="{{site.url}}{{site.baseurl}}demos/tdrive/"></iframe>
	<figcaption>T-Drive data sample from Microsoft Research, generated by Salt and visualized with Leaflet - <a href="{{site.url}}{{site.baseurl}}demos/tdrive/">View Fullscreen</a></figcaption>
</figure>

# Explore and Share data, visually

> **Salt** is a library for creating interactive visualizations to explore massive datasets.

Visualizing big data is hard. Overwhelming amounts of information often motivate the creation of highly aggregated visualizations, which can conceal localized patterns behind sums and averages. **Salt** helps you *transform* your data, so that it can be explored interactively at increasing levels of detail.

In the example above, pickups and dropoffs from [NYC taxi data](http://www.andresmh.com/nyctaxitrips/) are plotted across hours of a single day. Like a photograph, meaningful features and insights reveal themselves as you pan and zoom from an aggregate high-level view down to every conceivable local region. Here, **Salt** is used to project source data into the [torque](https://github.com/CartoDB/torque) format, and plotted using [Leaflet](https://github.com/Leaflet/Leaflet). [Try it yourself](https://github.com/unchartedsoftware/salt-examples/tree/master/torque-example)!

## Scalable Analytic Layered Tiles

**Salt** enables the visualization of non-numeric spatial data as well. Below, top Twitter hashtags have been plotted in word clouds by region, above the Taxi dataset. Zooming in de-aggregates the word clouds, allowing you to explore local trends, while zooming out gives you a high-level overview of hashtag usage in the New York City area.

**Salt** makes it easy to generate many kinds of visualizations including geographic heatmaps, cross-plots or time series, with meaningful contextual overlays in a wide variety of data formats that enable analysis and exploration at every scale.

<figure>
  <iframe width="100%" height="368px" src="{{site.url}}{{site.baseurl}}demos/taxi-twitter/"></iframe>
  <figcaption>Taxi pickup and dropoff locations with tile-based analytics overlay summarizing the top Twitter hashtags by region - <a href="{{site.url}}{{site.baseurl}}demos/taxi-twitter/">View Fullscreen</a></figcaption>
</figure>

## Ready to see your data?

Try the [Salt Examples](https://github.com/unchartedsoftware/salt), look at the [docs](/docs/scaladoc/#software.uncharted.salt.core.generation.TileGenerator), or [contact us](mailto:{{site.email}}) for more information.