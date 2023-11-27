## High-dynamic range imaging - The Debevec-Malik method

The goal of this project is to implement the high-dynamic range imaging (HDRI). HDRI is a method in photography that combines multiple exposures of the same subject matter with varying exposure levels to create more natural looking and brightened images. HDRI as a topic has several different algorithms. In this project, we will utilize the Debevec-Malik algorithm, published at UC Berekeley by Paul E. Debevec and Jitendra Malik. The algorithm is a method to recover high dynamic range radiance maps from images taken using convential imaging equipment. Using information from all the images, it fuses multiple photographs into a signle, high dynamic range radiance map. The pixels in the map have values proportional to true radiance values in the scene.

Our goal is to separate the algorithm into easily digestable steps that make it simple to understand how the results are achieved. We will use a variety of examples to show the end result and compare our implementation against one by OpenCV, exploring any potential differences and reason about where they may originate.
