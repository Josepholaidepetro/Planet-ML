# Planet-ML

Here, a multi-label classification model was used to track the human footprint in the Amazon rainforest.

There are 17 possible tags that can be in a given satelite data: agriculture, artisinal_mine, bare_ground, blooming, blow_down, clear, cloudy, conventional_mine, cultivation, habitation, haze, partly_cloudy, primary, road, selective_logging, slash_burn, water.

Methods:

1. Custom training generator was used
2. Inception_resnet_v2 was employing for training and fine tuning.
3. fbeta metric was used.
4. fbeta score of 91.8% was achieved.
