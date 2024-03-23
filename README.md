## brocoli (Louis Villemure)

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

The following GUI test is the same for all test cases, (only the scaling factor and number of servings will vary)

Click on recipe -> Click on display recipe button -> Click on settings to change servings and scaling factor (equaliser icon) -> Ajust scaling factor and number of serving -> Press Ok button

Expected outcome is that the ingredients quantity is adjusted for all ingredients or "not adjusted" will be printed next to the ingredient quantity.

### 3

a.

![EventFlowDiagram drawio (1)](https://github.com/lo-vil/temp/assets/94203138/9ea63275-075f-4739-8cad-574d6fd339ec)

b.

![Screenshot 2024-03-22 at 9 37 43 PM](https://github.com/lo-vil/temp/assets/94203138/23fb3e0e-8374-4652-b6b9-c1cc2f597f2b)

![Screenshot 2024-03-22 at 9 37 48 PM](https://github.com/lo-vil/temp/assets/94203138/7bc06caf-d160-4bdb-81b4-f20ac41e997d)

![Screenshot 2024-03-22 at 9 37 54 PM](https://github.com/lo-vil/temp/assets/94203138/687a5878-af1d-4189-88c3-aedfdddfe430)


### 4

a. 

![Screenshot 2024-03-22 at 8 11 45 PM](https://github.com/lo-vil/temp/assets/94203138/d796141e-0b2c-458c-a94a-03e3b8849100)


b. 

True: (oldImage == null) and (imageHasBeenSet() == true)

False: (oldImage != null) or (imageHasBeenSet() != true)


2 Clauses : 
* oldImage == null 
* imageHasBeenSet()

This method can't be tested at the GUI level, meaning no matter the interaction with the UI, this method behaves the same way. It ensures that the clean up method for getting rid of the old image when a new image is uploaded worked.
