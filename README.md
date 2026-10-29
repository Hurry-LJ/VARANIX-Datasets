# Geometry data

Each file in `torus/` describes two ordered operands: `operands[0]` is A and `operands[1]` is B. Values are decimal strings rounded to the shortest representation that parses back to the same IEEE-754 binary64 value. The string `"-0"` preserves negative zero.

Torus entries store their center, X/Y/Z axes, major radius, and minor radius. Cylinder and sphere entries store a center, axes, and radius; cone entries also store the semi-angle. Planes store location, normal, X direction, and whether that direction is present. The files contain geometry only; test settings, source links, and run results are kept outside this repository.
