# udacity-project3

This project was a challenge because I wanted to make the card effect using blur. However the blur filter not only overlaps the image itself with a fuzzy edge - it also reduced the bluring effect a few pixels before the edge. So you get this poor blurring effect up and past the edge of the image.

I solved this with overflow: hidden; to prevent the bluriness overlay the image. I also create a bit area for the blur to carry across giving a much crisper edge and effect. It took a lot of trial and error to finally figure out a good solution.
