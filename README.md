Basic instructions:

Run bin/do_split_generic <map-type> <country> <file>
map-type is one of default, car, bike, hiking, skating, skiing, fns
country is one of at, ba, be, carib, ch, cz, de, dk, es, fi, fr, gb, gcc, hu,
it, lu, nl, no, tr.
file is the pbf file to convert.

bin/do_mkgmap_generic <map-type> <country>

Note that bounds files are needed.

For contour lines run do_contours_generic <map> <country> <input>
instead of do_split_generic and do_mkgmap_generic.
