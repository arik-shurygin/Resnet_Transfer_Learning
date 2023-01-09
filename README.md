# Resnet_Transfer_Learning
This is an experiment preformed to learn about transfer learning and different types of classification heads on pretrained networks, particularly Resnet18. This repository finetunes a pretrained resnet18 model on the Stanford Cars dataset.

The first model, testing in resnet18_finetune notebook, uses pretrained resnet18 weights with a simple linear classification head, achieving a validation accuracy of around 28%.

The second model, using simple regularization techniques such as pixel normalization and dropout, as well as a two layer classification head, achieves 40% validation accuracy.

Because these expeiriments were done on my local PC, I was limited to using resnet18, and not any of the stronger resnet weights. I was training on a CPU with no cuda compatible GPU on the local machine.

This is a simple experiment meant to highlight my knowledge of CNN's and transfer learning, not meant to be the baseline of any large scale projects. I do not own the data this model was trained or finetuned on. Find Stanford cars dataset here: http://ai.stanford.edu/~jkrause/cars/car_dataset.html

