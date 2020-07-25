# Global-Wheat-Detection
My progress &amp; helping materials in Kaggle competition

I guess idea to delete boxes with big sizes is good so just do it. We checking all boxes w/ big area and decide delete or not delete this, function looks like this:

![text](https://github.com/germanjke/Global_Wheat_Detection/blob/master/readme_images/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%20%D0%BE%D1%82%202020-07-18%2013-09-18.png)

The main model of this competition was yolov5 so this was a choice, but some problems with MIT license so idk what is going now :) 

07/25 Today, after a long review of boxes with a large area, I concluded that a large area is in any case very bad for our task. The sprout of wheat can be long, but it cannot be thick, the area must not be large. There are 147k boxes in the dataset, I plan to remove about 10 percent of the boxes with a large area.
