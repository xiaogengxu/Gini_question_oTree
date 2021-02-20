# Gini_question_oTree
This app is developed to ask ideal wealth distribution among five quintiles.
I find it hard to develop a multi-thumb slider for this particular question.
Because the choice of one slider influences the eligible range of other sliders.
The algorithm behind has two ways.
First, the sum of the five quintiles should be 100%.
Second, the top quintile should be at least 20% and the second quintile should be at least 20%*(100-top quintile), et cetera.
