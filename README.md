<h1 align="center">
  <a href="https://github.com/apa-newsroom/austrian-neighbourhood-maps/">
    <img src="/.github/hero-map.gif" alt="" role="none" style="max-width: 80%" />
  </a><br />
  Austrian Neighbourhood Maps / Österreichische Grätzlkarten
</h1>

<h3 align="center">
  Let’s put regional media coverage on the map!
</h3>

<p align="center">
  <a href="https://github.com/apa-newsroom/austrian-neighbourhood-maps/">
    <img src="https://img.shields.io/badge/cities-1-green.svg" alt="" role="none" />
  </a>
  <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
    <img alt="Creative Commons License" style="border-width:0" src="https://img.shields.io/badge/licence-CC--by-green.svg" />
  </a>
</p>

<p align="center">
  <a href="#About">About</a> •
  <a href="#Using-the-Austrian-Neighbourhood-Maps">Usage</a> •
  <a href="#Contributing-to-the-Austrian-Neighbourhood-Maps">Contribution</a> •
  <a href="#Attribution">Attribution</a>
</p>

## About

When discussing the coverage of the Viennese elections in 2020, we had the idea of enhancing the presentation of regional results.

Unfortunately, many of the 23 districts of Vienna are too big for local evaluations.
The 10th district, Favoriten, for example would be the third largest city of Austria in respect to population.
Using the results of single electoral districts, on the other hand, is no good option as well, as they are too small and the inhabitants of Vienna do not have emotional bonds and do not even know which electoral district they belong to.

For that reasons the APA-editorial staff and the Data + Graphics-team developed a map of urban neighborhoods, the so called “Wiener Grätzl-Karte”.
Cooperating with <a href="https://www.ogm.at">OGM research & communication</a> and <a href="https://www.imgraetzl.at">imgrätzl.at</a>, we succeeded in splitting Vienna into 137 urban neighborhoods (“Grätzl”), that are based on the census districts of <a href="https://pic.statistik.at/web_de/statistiken/index.html">Statistik Austria</a>, with neighborhoods like “Nordbahnviertel”, “Per-Albin-Hansson-Siedlung” or the “Döblinger Cottage”.
This map has been successfully used for the Viennese elections and has also been adapted to the Presidential Election 2022 and the European Election 2024.

Since then, this map has been continuously refined, particularly during our “Wiener Datengschichtn”-project in which we combined existing open data and NLG-technology in order to tell local stories about Vienna.

We are convinced that not only Viennese people but also inhabitants of other cities have an emotional bond to their local neighborhood and love to read stories or see infographics on that subject.
So we have decided to open source the project.
We hope that the data-savvy community will help refining our urban neighborhoods and start to define urban neighborhoods in other cities as well.

## Using the Austrian Neighbourhood Maps and Legal Requirements

As of June 2024 there are three different maps: 

The **[standard map](https://github.com/apa-newsroom/austrian-neighbourhood-maps/tree/bptest/vienna/zg2022)** is based on the [statistical districts](https://www.data.gv.at/katalog/dataset/0adc90c9-ac6b-47ef-aa83-b7780594720c) ("Zählbezirke"). It bundles the 1.368 statistical districts for the city of Vienna into 137 neighborhoods ("Grätzl") as defined by the mapping in [mapping_graetzl_zaehlgebiete.xlsx](https://github.com/apa-newsroom/austrian-neighbourhood-maps/blob/main/vienna/mapping_graetzl_zaehlgebiete.xlsx). You can use this map to visualize statistical data on a neighbourhood level. 

The **[electoral map for the Presidential Elections 2022](https://github.com/apa-newsroom/austrian-neighbourhood-maps/tree/main/vienna/bp2022)** is based on [electoral districts](https://www.data.gv.at/katalog/dataset/79c1030d-5cf6-4d58-ade6-02f66fb4dffb) for the Presidential Elections 2022.

The **[electoral map for the European Elections 2024](https://github.com/apa-newsroom/austrian-neighbourhood-maps/tree/main/vienna/eu2024)** is based on [electoral districts](https://www.data.gv.at/katalog/dataset/79c1030d-5cf6-4d58-ade6-02f66fb4dffb) for the European Elections 2024. 

You can use these maps to visualize election data on a neighborhood level. Since electoral districts in Vienna change between elections, the electoral map needs a new update with each election. The next update will be published for the General Election in Autumn 2024. 

The maps are available in [GeoJSON](https://github.com/apa-newsroom/austrian-neighbourhood-maps/blob/bptest/vienna/bp2022/graetzl_bp2022.json) format with a [preview-file](https://github.com/apa-newsroom/austrian-neighbourhood-maps/blob/bptest/vienna/bp2022/graetzl_bp2022.html). For allocating statistical or electoral districts to the different neighborhoods, please refer to the [mapping-files](https://github.com/apa-newsroom/austrian-neighbourhood-maps/blob/bptest/vienna/bp2022/mapping_graetzl_sprengel_bp2022.xlsx).

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a> (see [Attribution](#Attribution) for details).

## Contributing to the Austrian Neighbourhood Maps

We’re happy to welcome new contributors, either improving on our existing maps, or providing maps for uncovered cities.
In order to collaborate, please get in touch with us first, via email, so we’ll be able to sort out the details.

## Attribution

If you use our data, please quote us as: "APA, Datenquelle: [Stadt Wien](https://digitales.wien.gv.at/ogd-nutzungsbedingungen) data.wien.gv.at"
