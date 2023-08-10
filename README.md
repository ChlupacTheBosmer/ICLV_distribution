# ICLV

This is a distribution version of ICLV - Insect Communities Label Verifier. The purpose of this archive is to provide a simple, lightweight, installation-less way of distributing the application that allows the user to create, check, and edit label creation for YOLO object detection and sort through images.

## Instructions

1) Unarchive the "ICLV - distribution.zip".

2) To run the app open iclv/iclv.exe

3) Unarchive the "test frames.zip" for a series of test frames and accompanying label files.

![obrazek](https://github.com/ChlupacTheBosmer/ICLV_distribution/assets/29023670/ae49087e-5bb2-4744-8a6a-73db25f56d57)

## Controls

![image](https://github.com/ChlupacTheBosmer/ICLV_distribution/assets/29023670/e1446252-8ad9-4e86-bd94-2aa14e18285d)

A - Mark the image as "wrong"

D - Mark the image as "correct"

Space - Mark the image as "None" - neutral


W - Select the previous label

S - Select the next label

E - Edit selected label

F or Enter - confirm changes when resizing a label

R or BackSpace - delete the selected label

Q - Add label


X - Previous frame

C - Next frame

## Workflow

1) Once the app is opened select a folder in which there are both the image files and the accompanying label .txt files. Then the user interface will open. 

2) In the upper part of the screen, the image with any detected labels will be displayed. The details of each (colour-coded) label are in the left panel. You can change the category, edit, or delete the label.

      **Changing category:** Simply select the correct item in the dropdown menu.

      **Selecting labels:** You can change the label affected by the pressed keyboard shortcuts using "W" and "S". The selected label is marked by the red border around its properties in the left panel.
      
      **Editing label position:** Click the "Edit" button. The appearance of the respective label will change and you can modify the position of the label's corners by dragging them to their new position. Press "F" or "Enter" to confirm the changes. You can also triger the edit mode by selecting the label and pressing "E".
      
      **Deleting label:** Simply click the "Delete" button or press "R" or "BackSpace" when you have selected the correct label.
      
      **Add label:** Click the "Add" button and draw a rectangle (starting in its upper left corner) around the object in the image.
      
      **Moving to another image:** You can either press the "next" or "previous" buttons to move between images, or you can use the lower panel and click any thumbnail to move to that specific image. The red border marks the currently displayed image, Blue border marks the last displayed image. That is useful when quickly checking ahead if anything changes or if a bunch of images can be quickly skipped and marked as "wrong" etc. You can also use "X" and "C" to navigate between images.
      
      **Saving changes to label file:** Any changes to the label .txt file are saved once the user transitions to another (next, previous, thumbnail selected) image.
      
      **Sorting into folders:** When the application is closed, images marked as "wrong" and "correct" will be moved to their respective folders. Images marked as "None" will stay in place. You can use the shortcuts "A" - mark as wrong or "D" mark as correct and "Space" mark as None and you will be automatically moved to the next image.

## Notes

1) When reviewing labels that have more than the two recognised categories (0 - other visitors, 1 - lepidoptera) all other categories are treated as category 0. However, lepidopterans will also be treated as 0 and must be manually corrected.

2) Files are moved once the app is closed.

3) Changes to the .txt file are saved once you move to another image.
