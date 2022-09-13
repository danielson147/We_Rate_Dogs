# We_Rate_Dogs
Introduction: This article will describe and displays the three (3) insights and
one (1) visualization from the We Rate Dogs projects. The following are the
insights:
1. Breed of dog with more social appeal
2. Display the dog with highest prediction and the subsequent insight from it. 3. Dogs types with highest rating
1. Breed of dogs with more social appeal: The sum of each type is
determined by calling value_count() function on each of ‘doggo’, ‘floofer’,
‘pupper’ and ‘puppo’ fields. The total sum is therefore determined by adding
each respective sum together. The percentage of each dog type was
calculated by the following formula:
percent_doggo = (sum_doggo/sum_dog) * 100
This was computed for all dog types.
It was found out that 66% of dog type were pupper while the other dog type
made up 44%. This shows that pupper has more social appeal than any other
dog type and will be suitable for movie or television commercial. 2. Display the dog with highest prediction and the subsequent insight
from it: The pillow was installed to display the dog with highest confidence
level of prediction in the third column. The particular dog was identified by
calling idxmax() function on the ‘third_conf_level’ field. The image was
retrieved from the URL using
urllib.request.urlretrieve(https://pbs.twimg.com/media/CfFNk7cWAAA-hND.jpg
The display was a young pupper called Eskimo Dog. This actually agree with
our earlier assertion in one (1) above. 3. Dogs types with highest rating: The dog with the highest rating
determine from we_rate_dog_df by calling idxmax() function on the
DataFrame. The value return the details for Bluebert which has a rating of
50.0. Unfortunately, its dog type was not stated
