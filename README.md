# UCCS-UB-guitar_dataset:

This is the dataset used in the following project: https://github.com/AlbertMitjans/chord-detection

#### Find bellow the structure of the dataset:

- **0:** contains 180 jpg images downloaded from Google and 3 csv files for each image with annotations of the coordinates of every visible finger, fret and string.
- **1:** contains 208 images taken with a Nikon camera, 4 csv files with annotations of the coordinates of every visible finger, fret and string and the location of the left hand.
- **2:** contains 208 images taken with a Nikon camera with a higher vision angle, 4 csv files with annotations of the coordinates of every visible finger, fret and string and the location of the left hand.
- **videos:** folder containing 21 different videos (.mov) of three different people playing the guitar, together with 21 csv files containing a list of the chords played at every frame of every video, and 21 mp4 videos with the outputs obtained.
- **train.txt:** contains the path of 80% of the images of the aforementioned folders.
- **val.txt:** contains the path of the remaining 20% of the images of the aforementioned folders.
- **labels:** contains a list with the chords of the images in all folders. The first column determines whether the label is from folder 0, 1 or 2.
- **tabs.xlsx:** contains the tablature of the 14 main guitar chords (C, Cm, D, Dm...).
