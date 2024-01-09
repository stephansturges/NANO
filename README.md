## Use this button to try the model on Roboflow!

<a href="https://universe.roboflow.com/neural-autonomous-navigation-observer/nano-by-stephan-sturges/model/">
    <img src="https://app.roboflow.com/images/try-model-badge.svg"></img>
</a>

## What is this?

NANO is a set of short-range / low-rez / low-altitude trained YOLOv8-nano detection and segmentation model that detect a few simple things in RGB imagery. They are pretty basic for now.

It's free to use so knock yourself out! Just make sure to follow the Ultralytics terms of service around commercial use (https://github.com/ultralytics/ultralytics) since this uses their code for training.

Output classes: 

0 --> 'person'

1 --> 'bike'

2 --> 'light_vehicle'

3 --> 'truck'

4 --> 'bus' 

# Does it work?

It's not bad... it's a nano model so it's super fast for your edge devices... but is struggles with small objects that are far from the camera. You can run it on a cropped input of your complete frame to get pretty good performance. See the video below.


![output](https://github.com/stephansturges/NANO/assets/20320678/1000d8b0-480f-463b-91b4-018f63ca4529)


As you can see: the size of the neural network makes it pretty ineffective at longer ranges, which is expected. 




## License (MIT)


Copyright 2023 Stephan Sturges

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

