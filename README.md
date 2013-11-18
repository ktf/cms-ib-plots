## Client only summary pages.

Initial setup for a set of web pages with summary information about IBs.

The goal is to use [D3](http://d3js.org) and associated extensions to build web
pages client side, without using any server side plotting.

## Deployment

The goal is that these pages are self contained, so that copying them in the
correct destination is enough to deploy them.

In case of CERN there is a jenkins rule `web-deploy-summary-pages`, which takes
care of it.

Data is prepared by the `web-summary-data` page.

Web pages are visible from <https://cmssdt.cern.ch/SDT/summary>.
