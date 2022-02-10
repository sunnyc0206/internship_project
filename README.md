# internship_project

Given Figma UI that was implemented using SwiftUI along with the functionalities that were mentioned.

The main elements of the UI are the filter, the horizontal scrollable product cards, and the vertical scrollable unique products. (Fig01)
Each product is loaded in from a random JSON file, which is parsed into product, state, and city array to implement the Filter function properly. (Fig02)
A custom bottom popup card view was used to display the filters available to the user. (Fig03)
Result of the home screen after all of the filters have been applied, as indicited by the Filter button.(Fig04)

Dropdown functionalities:-
1)Products-dropdown should be the list of product names. The content of dropdown will be all the product names received in list of products in api call.
2)State-dropdown needs to be the list of State Names extracted from the list of products. If a product is already selected then it should only show list of state for that product.
3)ity-dropdown needs to be the list of City Names extracted from the list of products. The dropdown should only show list of cities of the selected state (If any state selected) only.

![1](https://user-images.githubusercontent.com/99381187/153338985-5d180a2d-952e-4990-8a76-ab795967379c.png)
![2](https://user-images.githubusercontent.com/99381187/153339004-8a5a41eb-ac63-4ed3-a98c-472512f02c66.png)
![3](https://user-images.githubusercontent.com/99381187/153339008-a6d8e93b-963c-456f-b711-2f4ee0bbfa1a.png)
![4](https://user-images.githubusercontent.com/99381187/153339012-ad837b78-cefe-4b92-b5f6-73e6e27d26d1.png)
