# Titanic Viz
A visualization is created using the Titanic dataset

## Summary:
The demographics of the people who either died or survived when the Titanic crashed is shown in this visualization. 
Older men died a lot trying to save their families. The ones from the lowest passenger class (class = 3) died the most. 
Having more money and hence higher passenger classes (class 1 & 2) increased the chances of survival. 

## Design:
### Initial design:
Since comparison needs to be done among various passengers of various demographics, a bar chart was an obvious choice.
A stacked bar chart showing fares v/s passenger class stacked by gender is used to show how fare prices varied by passenger class for both men and women. 
Also, I wanted to show how the age of the various passsengers varied. I considered showing a separate bar chart. But then I thought that I should
use the same chart with a different encoding. Hence, a bubble chart showing age v/s passenger class stacked by gender is used to represent 
the distribution of average age for the various passenger classes by gender. I wanted to add some animation too. 
Both of these can be made to transition using an animation based on whether they were dead or they survived. 
Color was used as a visual encoding to differentiate between male and female categories. 

### Second attempt:
As per the initial feedback received, some manual intervention was needed in the visualization to pause as per convenience.
To allow user to pause animation and play it again as per will, two buttons were added.

### Third attempt:
The feedback that I got was that the buttons and the font used for the corresponding text earlier looked like being part of some 1990's HTML page.
Hence, I decided to make them look better. To add to that, since they were on top of the graph, it drew unnecessary attention. 
So, the buttons were customized and added to the bottom. There was confusion with regards to what was represented by the bubbles and the bars.
Text was added to the bottom to denote what the bars and the bubbles represent. The font was made consistent too.

### Fourth design:
The feedback received was that without the counts in the individual categories, no suitable comparison could be made. I tried adding the counts along
with the text obtained on the mouse over popup but that was cumbersome. It is also not hover over each bar and bubble and keep note of the counts to compare.
Also, the feedback received was that the passenger fare and the class are related and hence showing both is redundant. Hence, the passenger fare axis is replaced
with the passenger count. Keeping two buttons is also not the standard for pausing and playing something. Hence, one button is kept whose 
text and border color change as per whether it is played or paused. 

### Fifth design:
The feedback received was that there were incorrect average age values, scales changed drastically and rates could help simplify the graph. The left side y-axis 
shows the survival percentage instead of the counts. The animation has been removed. For average age computation, algorithm has been updated and age for both dead and
survived in the various categories are shown in the chart. 

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

### Fourth attempt feedback:
•	What do you notice in the visualization?
    The visualization allows to compare the counts between the various groups.
•	What relationships do you notice?
    Among females who died, younger ones and those in passenger 3 class died more.
    Men in Passenger 3 class died the most.
•	What do you think is the main takeaway from this visualization?
    Older Men sacrificed their lives for their family members.
    Having more money helped in increasing the chances of survival.
•	How can the visualization be improved?
    Counts not needed. Rate of survival will simplify graph. 
    Scale changes drastically on animation change. 
    Average age values are incorrect.

## Resources:
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_price_range_lollipop
http://jsbin.com/hosobo/4/edit?js,output
http://jsfiddle.net/T6ZDL/4/