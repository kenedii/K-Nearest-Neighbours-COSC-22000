# K-Nearest-Neighbours-COSC-22000
K-Nearest Neighbours algorithm from scratch for Binary classification. Made for COSC-22000.

Data used: Dominos: [(3,4),(4,5),(7,3), (3,6), (5,3)],

Pizza Hut: [(-3,-4), (-4, -2), (-3,-8), (-5,-6), (-3,-3), (-3,-2)] 

def new_point_class(new_point, data, k=3, classifier='mode'): returns class of new point as str

new_point: (0,0) ordered pair of point to classify

data: dict. must contain key for 'points' dict variable 

k: number of nearest neighbours to consider

classifier: 'mode' recommended. 

     'mode': # Calculate the mode of the second numbers (Mode of the class of the K nearest neighbours)

     'sum': # Uses the sum of the binary class representation of the k nearest neighbours to classify the new point (only works for binary classification)
