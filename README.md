# Welcome to FaceTag.AI

**FaceTag is a program that allows for admins to track users throughout a building's network of security cameras. The program records users' movements across multiple camera streams to provide real time locations of personel. The program is also able to be used with singular cameras to identify people at a check-in or ticket desk.**

### Demo Video

https://www.youtube.com/watch?v=cQ1nDq6YIlg

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/cQ1nDq6YIlg/0.jpg)](https://www.youtube.com/watch?v=cQ1nDq6YIlg)

## Recognition Accuracy

![Recognition Accuracy](http://i.imgur.com/ccrLZpF.png "Recognition Accuracy")

## System Processing Capability

Time to find and identify 1 face in frame-

-With GPU: 1.8474 seconds

-Without GPU: 1.6474 seconds

Program is able to process X streams, looking for faces every Y frames

![System Speed](http://i.imgur.com/mGNXlLk.jpgg "System Speed")

## System Overview
### What's Inside?

The core FaceTag.AI program is only able to process a single video stream at a time. This means that in order to view all the streams in a camera, the main command program creates AWS instances for each camera which send the recognized data to the central MySQL database. This database is what is displayed on the UI home page.

![System Diagram](http://i.imgur.com/lRiL8RD.jpg "System Diagram")
