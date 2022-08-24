# -Pollution-Measurement-from-Dust-over-Road-Side-Plant-Leaf
This Work give us an overview of our project Pollution Measurement from Dust over Road Side Plant Leaf.The main objective was to make an accurate assessment of pollution levels, pollution vehicles and develop water sprinkling and techniques to estimate pollution loads in each city. We have used large datasets (images of different plant leaves) to find accurate pollution measurements. We’ve used a dataset (plant leaves) from different parts of India. We use Keras library to generate/Augment image.We train sequential model to find pollution in road side. Till now, Accuracy is 92%.

Problem Discussion

Dust is a major concern in urban areas .It has been estimated that about 30 million tons of dust enter the atmosphere each year worldwide. 
In fact, dust when inhaled can increase breathing problems, damage lung tissue, and aggravate existing health problems. In addition to health concerns, dust generated from various activities can reduce visibility, resulting in accidents. By the use of plant leaves we can detect pollution in that area .
Measure Pollution level so plants that Absorb Pollutants can be planted in a particular locality. 
Here we first click an image of a leaf which then scans it and runs the program which undergoes various processes and gives out a result of how much dust is there in the locality. If there is dust on leaves, we can build a mechanism that can sprinkle water to wash the plants. 



Implementation Details

Create Datasets(picture of leaves)
  i) Summer Season (150 photos)
  ii) Rainy Season(50 photos)
  iii) Winter Season(300 photos)

Coding part progress:
  i)Convolutional Neural Network
  ii)Data augmentation
  iii)Pooling(maximum)
  iv)Padding
  v)Activation layer
  vi)Stride
  vii)Train sequential model
  viii)Find accuracy



Implementation of Problem

The following steps that we used to solve the problem are following:

	Step 1:Firstly Create a Datasets of 500 photos.
	Step 2:Import Library Such as Numpy,Os,matplotlib,pandas for   calculation and plotting image on graph.
	Step 3:For training of Model Import keras library.
	Step 4:Use Adam optimisers for computations,and the accuracy or analysis.
	Step 5:After Compiling the code of the built model(Sequential Model).
	Step 6:Once the training is completed and analyzed for a fixed number of epochs,we can move ahead to the next step of evaluation and making predictions.
  	Step 7:The deployment Stage is the final Stage of the model



