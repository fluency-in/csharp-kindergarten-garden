# C#: Kindergarten Garden

Write a program that, given a diagram, can tell you which plants each child in the kindergarten class is responsible for.

The kindergarten class is learning about growing plants. The teachers
thought it would be a good idea to give them actual seeds, plant them in
actual dirt, and grow actual plants.

They've chosen to grow grass, clover, radishes, and violets.

To this end, they've put little styrofoam cups along the window sills,
and planted one type of plant in each cup, choosing randomly from the
available types of seeds.

```plain
[window][window][window]
........................ # each dot represents a styrofoam cup
........................
```

There are 12 children in the class:

- Alice, Bob, Charlie, David,
- Eve, Fred, Ginny, Harriet,
- Ileana, Joseph, Kincaid, and Larry.

Each child gets 4 cups, two on each row. The children are assigned to
cups in alphabetical order.

The following diagram represents Alice's plants:

```plain
[window][window][window]
VR......................
RG......................
```

So in the row nearest the window, she has a violet and a radish; in the
row behind that, she has a radish and some grass.

Your program will be given the plants from left-to-right starting with
the row nearest the windows. From this, it should be able to determine
which plants belong to which students.

For example, if it's told that the garden looks like so:

```plain
[window][window][window]
VRCGVVRVCGGCCGVRGCVCGCGV
VRCCCGCRRGVCGCRVVCVGCGCV
```

Then if asked for Alice's plants, it should provide:

- Violets, radishes, violets, radishes

While asking for Bob's plants would yield:

- Clover, grass, clover, clover

Follow these instructions on how to [get your C# development environment set up][csharp-installation].

The exercises use NUnit. Follow [this guide][nunit-guide] to get started.

[csharp-installation]: https://github.com/exercism/xcsharp/blob/master/docs/INSTALLATION.md
[nunit-guide]: https://github.com/exercism/xcsharp/blob/master/docs/TESTS.md

## Source

Random musings during airplane trip. [http://jumpstartlab.com](http://jumpstartlab.com)

This exercise is from the [C#][csharp] track on [Exercism][exercism]

[exercism]: http://exercism.io
[csharp]: http://exercism.io/languages/csharp



