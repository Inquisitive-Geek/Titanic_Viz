# Titanic Viz
A visualization is created using the Titanic dataset

## Summary:
The demographics of the people who either died or survived when the Titanic crashed is shown in this visualization. 
Older men died a lot trying to save their families. The ones from the lowest passenger class (class = 3) died the most. 
Having more money and hence higher passenger classes (class 1 & 2) increased the chances of survival. 

## Design:
### Initial design:
A stacked bar chart showing fares v/s passenger class stacked by gender can show how fare prices varied by passenger class for both men and women. 
A bubble chart showing age v/s passenger class stacked by gender can show the distribution of average age for the various passenger classes by gender.
Both of these can be made to transition using an animation based on whether they were dead or they survived.
Color was used as a visual encoding to differentiate between male and female categories. 

### Second attempt:
To allow user to pause animation and play it again as per will, two buttons were added.

### Third attempt:
The buttons were customized and added to the bottom. Text was added to the bottom to denote what the bars and the bubbles represent.
The font was changed as suggested.

### Final design:
The passenger fare axis is replaced with passenger count. One button is kept whose text and border color changes as per whether it is played or paused. 


## Feedback:
### Initial feedback:
Transition is too fast to interpret anything.

### Second attempt feedback:
•	What do you notice in the visualization?
    Female survivors are more than male survivors except for class 1
    Female in class 2 have been the least casualties
•	What questions do you have about the data?
    I am not sure how the Fare value fits in the graph
•	What relationships do you notice?
    Passenger class 2 are relatively younger
    Survivors are more in class 1, while the dead are almost equal. This indicates, class 1 had more people than the other classes
•	What do you think is the main takeaway from this visualization?
    Most people that are dead are males in all classes
•	Is there something you don’t understand in the graphic?
    Fare value in the graph
    Scale changing is confusing
    Unable to relate between age and fare in charts
    Put the pause and play buttons below the chart
    See if divided by age there is any correlation
    Font of “Clicking Pause pauses the animation. Clicking Play re-plays it.” Needs change
    Counts could be shown.

    
### Third attempt feedback:
Without counts, comparison is very difficult.
Since passenger fare and class are related, no need to show both.
2 buttons for Play and Pause not needed. Try to create one button.

### Final feedback:
•	What do you notice in the visualization?
    The visualization allows to compare the counts between the various groups.
•	What relationships do you notice?
    Among females who died, younger ones and those in passenger 3 class died more.
    Men in Passenger 3 class died the most.
•	What do you think is the main takeaway from this visualization?
    Older Men sacrificed their lives for their family members.
    Having more money helped in increasing the chances of survival.

## Resources:
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_price_range_lollipop
http://jsbin.com/hosobo/4/edit?js,output
http://jsfiddle.net/T6ZDL/4/