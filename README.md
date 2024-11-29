# Tilegrams

A “tilegram” is a map made of tiles
where regions are sized proportionally to a dataset.

You can read more in
[our blog post](http://pitchinteractive.com/latest/tilegrams-more-human-maps/)
or the [manual](MANUAL.md).

## Development

### Setup
Despite many deprecations, npm v10.24.1 can install this project when it can call python2 (Python 2.7). Other setups might work.

After cloning the repository, run:

    npm i

### Running

Run

    npm start

Then access `http://localhost:8080/`.

### Deploying

To generate deployable assets, run:

    npm run build

They will be written to `dist/`.

## Dependencies

JavaScript is written in [ES2015](https://babeljs.io/docs/learn-es2015/)
using [Babel](https://babeljs.io/). Styles are written in
[SASS](http://sass-lang.com/). All assets are preprocessed with
[webpack](https://webpack.github.io/).

The Maker also depends on a pre-release `npm` version of `topogram`
(formerly `cartogram.js`) as seen in
[this PR](https://github.com/shawnbot/topogram/pull/26).

## Data Sources
[US Population Data](http://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=PEP_2015_PEPANNRES&prodType=table)

[Electoral Votes Data](https://www.archives.gov/federal-register/electoral-college/allocation.html)

[GDP Data](http://www.bea.gov/itable/)

[France Population Data](https://en.wikipedia.org/wiki/Ranked_list_of_French_regions)

## Base Map Sources
US states map:
[Natural Earth Data](http://www.naturalearthdata.com/downloads/)

<!---UK constituency map:
[Ordnancesurvey.co.uk](https://www.ordnancesurvey.co.uk/opendatadownload/products.html)
Contains OS data © Crown copyright and database right (2017),
[Ordnance Survey of Northern Ireland](http://osni.spatial-ni.opendata.arcgis.com/datasets/563dc2ec3d9943428e3fe68966d40deb_3)
Contains public sector information licensed under the terms of the Open Government Licence v3.0.

UK local authority map:
[http://geoportal.statistics.gov.uk/](http://geoportal.statistics.gov.uk/datasets/686603e943f948acaa13fb5d2b0f1275_2)
Contains OS data © Crown copyright and database right (2017),
[Ordnance Survey of Northern Ireland](http://osni-spatial-ni.opendata.arcgis.com/datasets/a55726475f1b460c927d1816ffde6c72_2)
Contains public sector information licensed under the terms of the Open Government Licence v3.0.--->

Germany constituency map:
[Bundeswahlleiter.de](https://www.bundeswahlleiter.de/en/bundestagswahlen/2017/wahlkreiseinteilung/downloads.html)
© Der Bundeswahlleiter, Statistisches Bundesamt, Wiesbaden 2016,
Wahlkreiskarte für die Wahl zum 19. Deutschen Bundestag
Basis of the geological information © Geobasis-DE / BKG (2016)

# License

This software is distributed under the [ISC](https://spdx.org/licenses/ISC.html)
license.
