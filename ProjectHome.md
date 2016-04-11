easy to show system performance and network flow

base on http://d3js.org and http://blog.bitjuice.com.au/2013/02/using-d3-js-to-visualise-hierarchical-classification/

check out demo at https://code.google.com/p/performance-graph/source/browse/#svn%2Ftrunk

ver 0.12(13-03-22)

bug fix:
take advantage of d3's data-join,so that only relevant paths but not all ones will be redraw.

ver 0.11(13-03-15)

features:
show description on each path(edge)

bug fix:
misspelling fixed.

know issues:
path descriptions are fixed unless redraw() is called in chrome 25.0.1364.160
see https://code.google.com/p/chromium/issues/detail?id=196523

ver 0.1

features:
1)tree and connectivity(network) are both supported.
2)draggable nodes.
3)able to custom the config and actions.

bug fix:
change dom property to class instead of dumplicated id.