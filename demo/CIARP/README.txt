Brief:

This script executes the Dynamic Trees method for image segmentation proposed in [1] 
with minor implementation changes, the distance between nodes are defined by the 
squared l2 norm and a new gamma scale parameter for neighbor nodes distance is introduced.
Equivalent results are obtained while introducing more flexibility.

Dataset obtained from the paper [2].

Requirements:

* PyIFT


Example:

python3 execute-dataset.py

References:

[1] Bragantini,  J.,  Martins,  S.B.,  Castelo-Fernandez,  C.,  Falcão,  A.X.:  Graph-based
image segmentation using dynamic trees. In: 23rd Iberoamerican Congress on Pattern 
Recognition (2018), to appear.

[2] Andrade F., Carrera E. V., "Supervised evaluation of seed-based interactive image
segmentation algorithms", In Proceedings of the 20th Symposium on Image, Signal Processing, 
and Artificial Vision, ISBN 978-1-4673-9461-1, Bogota, Colombia, pp. 225-231, September 2015.

