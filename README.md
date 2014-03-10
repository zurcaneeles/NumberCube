NumberCube
==========
public static int[] getCubeTosses(NumberCube cube, int numTosses)
  {
    int[] tosses = new int[numTosses];

    for (int i = 0; i < tosses.length; i++)
      tosses[i] = cube.toss();

    return tosses;
  }
