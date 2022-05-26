# ThermoDetect
To stop the spreading of COVID-19, many places have installed thermal cameras to stop people with fever to go in.

Well, this has ended up pretty bad. The cameras can only find out hotter spots, but these spots may not be forehead, which means that users of the cameras cannot know if the warned guy is really having a fever or not.

In this picture, you can see that the camera locked on both a person's head and another's arm. The latter is not what we are looking for.

![19](https://user-images.githubusercontent.com/81124939/170424126-a1d35ab6-04ae-4bf8-b97c-2873b814e165.png)

So here is our solution: an AI model to find out all the heads in a thermal image. If it is trained well, it can identify people with fever properly without being triggered by other hot stuff.
