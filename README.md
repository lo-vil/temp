### 1

Method:

![Screenshot 2024-03-22 at 8 12 49 PM](https://github.com/lo-vil/temp/assets/94203138/9a2cf9b6-51c2-4a4c-a7c3-c248355fab95)


a.

Parameters: String quantity, float scaleFactor

b.

![Screenshot 2024-03-22 at 8 01 49 PM](https://github.com/lo-vil/temp/assets/94203138/9603cfc6-24b1-4e8b-856d-a4999f083153)

![Screenshot 2024-03-22 at 7 25 58 PM](https://github.com/lo-vil/temp/assets/94203138/13bcc599-e6fd-4f1c-916e-64fd02fa448e)

c.

![Screenshot 2024-03-22 at 8 08 35 PM](https://github.com/lo-vil/temp/assets/94203138/d88830b0-914e-494b-b092-d499253f339c)

![Screenshot 2024-03-22 at 7 25 49 PM](https://github.com/lo-vil/temp/assets/94203138/f855bdfb-0a6a-4717-9f07-08339acb2ba5)


### 2

a.

Ajust number of servings -> Press Ok button

Expected outcome is that the ingredients quantity is adjusted for all ingredients or "not adjusted" will be printed next to the ingredient quantity

### 3

a.

![EventFlowDiagram drawio](https://github.com/lo-vil/temp/assets/94203138/24cb472e-1df3-4ace-aa35-57c835aa461a)

b.


### 4

a. 

![Screenshot 2024-03-22 at 8 11 45 PM](https://github.com/lo-vil/temp/assets/94203138/d796141e-0b2c-458c-a94a-03e3b8849100)


b. 

#### oldImageName is null and imageHasBeenSet() is true

* Preconditions:
  
  
Ensure that the application is running and accessible.

Load a recipe with an old image and ensure oldImageName is null initially.

Set a new image for the recipe.


* Steps:


Trigger the method removeOldImageAndCleanUpAnyTemporaryImages() by simulating user interaction (e.g., clicking a button or performing an action that calls this method).


* Expected Outcome:


cleanUpTemporaryImage() is called.

Since oldImageName is null and imageHasBeenSet() returns true, oldImageName should be updated with the current image name (recipe.getImageName()).


<br />

#### oldImageName is not null or imageHasBeenSet() is false

* Preconditions:
  
  
Ensure that the application is running and accessible.
  
Load a recipe with an old image and ensure oldImageName is not null initially.
  
Ensure that imageHasBeenSet() returns false.

  
* Steps:


Trigger the method removeOldImageAndCleanUpAnyTemporaryImages() by simulating user interaction (e.g., clicking a button or performing an action that calls this method).


* Expected Outcome:


cleanUpTemporaryImage() is called.

Since either oldImageName is not null or imageHasBeenSet() returns false, oldImageName should not be updated, and the method should exit without updating oldImageName.
