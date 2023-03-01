# UFO sightings
## Overview
Dana has tasked us with creating a dynamic webpage for UFG sighting. We will be displaying use of HTML and JavaScript to allow users to filter the data by inputting information such as; date, time, city, and etc.

![image](https://user-images.githubusercontent.com/124399950/222291704-708c63d3-0caf-43bf-a5bb-cbe68a09a29d.png)

## Results
We have successfully implemented the HTML webpage as desired by Dana. We have ingested the data set of UFO sightings. The default view upon loading the page shows all data results is displayed below
> ### Default

![image](https://user-images.githubusercontent.com/124399950/222291607-50af39c3-3d6d-4e9c-a34b-da41e4e67726.png)

As you can see the fill text gives examples to help the user understaand what options they have to filter by

> ### Single Filter

![image](https://user-images.githubusercontent.com/124399950/222291563-149ec739-ee1c-4dfb-b0aa-e70611c7d556.png)

The above screenshot  demonstrates that after entering a state's abbreviation (in this case __) into the state text field then clicking out it will filter the data to show the results chosen for the state. (_)

> ### Multiple Filters

![image](https://user-images.githubusercontent.com/124399950/222291536-4b549832-badb-4246-8c59-648058296f92.png)

The above shows that multiple filters can be entered to further narrow down the search. The algorithm tacitly assumes an AND type of search feature based on the criteria. 

## Summary
While this website provides a simple was of filtering through the dataset provided, there are some drawbacks and limitations. For example since the user must type in their data, they may enter data that doesn't exist within the dataset meaning no results, or if they happen to have a typo or misuse of capital letters. Also it may be deemed "not user friendly" if user doesn't knwo to click out of the input box
> ### Limitation example
![image](https://user-images.githubusercontent.com/124399950/222291506-5e141fbc-acea-4888-a625-5d51fa777a4f.png)


As you can see above, even when inputting the "grammatically" correct way for the state California "CA" no reults come up due to limitations
> ### Suggested improvements
* I believe if-else statements could be deployed to check for incorrect inputs: if the input is incorrect, a message will let the user know. 
* Another possible improvement to the filtering process would be to create a drop down list of data (dates or cities for example) that would allow the user to input queries on the data provided as opposed to needing to know what data is actually in the data set in order to search.
* A generate button to ensure user can get the information once inputted
