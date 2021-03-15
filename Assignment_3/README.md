
# Assignment:

This folder contains all the assignment details of part 2.1 and part2.2 here
## Presentation
1. Presentation Recording
2. Presentation slide 
## Part-1:
1. Assignment2_Part1_Image.pdf [Cloud training screenshots]
2. Assignment2_Part1_Text.pdf [Cloud training screenshots]
3. Assignment2_Part1_Video.pdf [Cloud training screenshots]
4. Assignment2_Part1_CustomTraining.pdf [Cloud training screenshots]
5. Assignment2_Part1_Tabular.pdf [Cloud training screenshots]
## Part-2:
1. Assignment2_part2.pdf [Cloud training screenshots]


############################################################################################################
The homework has 3 parts.

Generate data : 3 dimensions input and 2 dimensions output (unlike 2 dimensions input and 1 dimension output i provided in the slides) similar to how i explained in slides. (pick your own nonlinear equation to model it - similar to the example i had in the colab)

The output is 2 neurons - not one like in slide . each modelling one nonlinear function in 3 input dimension variables.

- plot the output post training as well as the real data  using tsne (given the input is 3 dimension and output is 1 dimension for each output neuron - we need to translate this to 2 or 3 dimensions using tsne plotting - sample colab https://colab.sandbox.google.com/drive/1IlzvNrWXR-2npz4PaLORHfVx3TmW41B (Links to an external site.)3   other examples https://colab.sandbox.google.com/drive/1uLNdjmJMcriJdcROBWNGkQR05jHHdeq9?usp=sharing#scrollTo=A7PwThT1q-Z (Links to an external site.)s. or https://thedatafrog.com/en/articles/visualizing-datasets/ (Links to an external site.)   - a lot of articles on how to visualize 4d data on 2d or 3d space (3d space is extra points - interactive 3d object - even more extra points. -- sample 3d wireframe  https://colab.sandbox.google.com/gist/vivek081166/7180433ad5a8cc56b28b4fe63736976a/wireframe.ipynb#scrollTo=XM3eDpwhTO17 (Links to an external site.)   https://medium.com/in-pursuit-of-artificial-intelligence/data-visualization-in-python-9aa1d9c2baec (Links to an external site.)   ))  https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html

for each of the below 7 parts you have to plot the target data and predicted data plots post training.

part a) Using pure Numpy to build a 3 layer neural network (with relu nonlinearity - this is different from the  2 layer i have provided in the colab in slide deck) to train on data - pick appropriate number of neurons in each layer and just use relu for non linearity.

part b.1) use pure pytorch tensor datastructure to build the same - do not use the auto differentiation yet. (check my pointers in the list of pytorch pointers)

 b.2) use the pure pytorch tensor data structure to build the same but with auto differentiation primitives

b.3 ) use the pure pytorch linear modules etc.,. - high level primitives and build neural network

 

part c.1) use pure tensorflow tensor datastructure to build the same - do not use the auto differentiation yet.

 c.2) use the pure tensorflow tensor data structure to build the same but with auto differentiation primitives

c.3 ) use the pure tensorflow keras  linear modules etc.,. - high level primitives and build neural network - make sure you use the Model subclassing (not the functional api or sequential api) as shown in the slides of the class. 

 

Please submit all the colabs (7 of them) in a single directory with proper readme.md file explaining brief details of the same.

 
 
