# Cyber-Physical Systems Testing Competition #
Starting this year, the [SBST Workshop](https://sbst21.github.io/) offers a challenge for software testers who want to work with self-driving cars in the context of the usual [tool competition](https://sbst21.github.io/tools/).

This repository represents one of the submissions to the competition. We have created a "SWAT" test case generation tool for self-drivng cars CPS, integrated with the code pipeline of the competion.
To launch the tool code, you should download the code from https://github.com/se2p/tool-competition-av competition repository and use the competition.py file, indication the location of the path of the "sawt_gen" module. Name of the (main) class implementing the test generator is SwatTestGenerator.

Here's an example of the command to use to lauch the SWAT tool (integrated with the competition code pipeline):

``` 
python competition.py \
        --visualize-tests \
        --time-budget 100 \
        --executor mock \
        --map-size 200 \
        --module-name  swat_gen.swat_generator \
        --class-name SwatTestGenerator
``` 
## SWAT tool principle of ##


Solarized dark |  Solarized Ocean  |  Solarized Ocean
:-------------------------:|:-------------------------:|:-------------------------:
<img src= "./figures/turn_left.png" width="200" height="300">  | <img src= "./figures/straight.png" width="300" height="300"> | <img src= "./figures/turn_right.png" width="200" height="300">




Turning right

Going straight
