# EAST-tesseract-OCR

We will use EAST model to get the ROI, i.e. the co-ordinates of the bounding boxes of text in the image.
We have used the specific layers for this purpose which are:

1. The coordinates of the bounding box of text.
2. The confidence score of the bounding box(we have used threshold probability 0.5)

We will then pass these cropped images containing text to the tesseract and take the predictions into a list.
