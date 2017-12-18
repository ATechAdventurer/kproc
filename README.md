# Processing with Kotlin

This project grows out of my desire to learn Kotlin and Processing
simultaneously. It is also an experiment to gain access to Processing's core
library (all those [graphics functions](https://processing.org/reference/))
without using its IDE. As it turned out, Processing and Kotlin can work together
quite seamlessly.

All programs are small and stand-alone. You need **Java 8** and **Gradle 4.4**
to build them:

- `gradle classes` to compile
- `gradle run` to see it

In chronological order:

1. [Bouncing Balls](https://github.com/nickoala/kproc/tree/master/balls): Eight balls bouncing in a window,
   modeling gravity and bouncing.

![Bouncing Balls](https://github.com/nickoala/kproc/blob/master/balls/balls.jpg?raw=true)

2. [Game of Life](https://github.com/nickoala/kproc/tree/master/life)

![Game of Life](https://github.com/nickoala/kproc/blob/master/life/life.jpg?raw=true)

3. [Fractals](https://github.com/nickoala/kproc/tree/master/fractal)

![Fractals](https://github.com/nickoala/kproc/blob/master/fractal/fractal.jpg?raw=true)

4. [Loci](https://github.com/nickoala/kproc/tree/master/loci): Follow a fixed point on a rolling circle. Some
   beautiful curves are traced out.

![Loci](https://github.com/nickoala/kproc/blob/master/loci/loci.jpg?raw=true)

5. [Cannon Game](https://github.com/nickoala/kproc/tree/master/cannon): Fire cannon balls at a target. Use the
   arrow keys to adjust the shooting angle and firepower, use spacebar to
   launch.

![Cannon Game](https://github.com/nickoala/kproc/blob/master/cannon/cannon.jpg?raw=true)

Thanks to [The Nature of Code](http://natureofcode.com/book/) for inspirations.
