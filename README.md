# The Mod Fac Test
A graphical experiment with multiplication in modular integer rings.

Demo here: https://nizabel.github.io/mod-fac-test/

The project was greatly inspired by a Numberphile video.

The project is also an experiment in using HTML, CSS and Javascript to build web apps and usable user interfaces.

The program is licensed under the MIT license.

The program uses artwork from https://feathericons.com, licensed under the MIT license by Cole Bemis

## The Math

The math behind the program is based on modular integer rings. (https://en.wikipedia.org/wiki/Ring_(mathematics))

A modular integer ring is a range of integers from zero to the module (set with '%' slider or the '%' value). Numbers in the ring can be added and multiplied. If the result is larger than or equal to the module then the result is adjusted using the modulo operation (https://en.wikipedia.org/wiki/Modulo_operation) such that the result is within the range.

Each of the pegs around the perimeter of the circle represents one value in the ring, starting with zero at the rght most (indicated by a double peg) and moving counter clockwise around the circle.

A line is drawn between to pegs if the mutiplication of the first value with the factor (set with '×' slider or the '×' value) results in the second value under the modulo multiplication of the ring.

## The Colors

There are three coloring methods used in the program. The first two are the same (circle and doucle cirlce) in that the figure is rendered using a single color. The first (cirlce mode) uses the color set with the color control (droplet), the second uses a color based on the color value, the module and the factor (added together).

The third method (patched circle) colors each line using a new color. The starting color can be set with the color control.

The fourth method (pie circle) colors each group using one color. The starting color can be set with the color control.
A group is the results of applying the multiplication recursively (r<sub>n+1</sub> = r<sub>n</sub> × f) until a peg that was previously visited is hit.

## The Play mode

When starting play the factor is increased gradually. In play mode the factor takes on non-integer values and the transition from one integer factor to the next can be observed. The rate of change can be increased (double chevron) and decreased (single chevron).
