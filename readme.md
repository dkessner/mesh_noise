# mesh noise

This project demonstrates ofMesh (and ofNoise).

It's based on Lewis Lepton's tutorial 67 on mesh noise.
[https://github.com/lewislepton/openFrameworksTutorialSeries](https://github.com/lewislepton/openFrameworksTutorialSeries)

Two notes:
- from tutorial: 'count' variable in double loop is used for 2D-1D index conversion
- using x and y positions (instead of index) gives 2D correlation in the noise (instead
  of correlation in the index)

```
source setenv
make
emmake make
```

