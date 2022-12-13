# AdvAttacksResearch
Research based on adversarial attacks. Latvian University, 1st course.
# Problem
An adversarial attack is a type of an attack that is used on an AI model. Usually it is used on an image classification model, but is it possible to use it on a regression model with few parameters?
Hypothesis:  An adversarial attack can be used on the regression model with few parameters. 

# The work
The main idea is to create a not very accurate regression model with few parameters. As an example, the model that predicts Dubai’s apartment price was created. Then, there is also a hypothesis, that adversarial attack will be more accurate on the model that heavy relies on one parameter, so was created second model, in which was added custom created parameter, which value depends on first model’s predictions. 

# Conclusion
It is possible to create an adversarial attack on the regression model with few parameters, but the result will be worse than on a model with a lot of parameters. The adversarial attack on a second model was as accurate as on the first. Although the model relies on this parameter value, the result was the same.
