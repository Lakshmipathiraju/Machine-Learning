# Machine-Learning
classification 

classification is the problem of identifying to which of a set of categories  a new observation belongs, on the basis of a training set of data containing observations whose category membership is known. 

example:
======== 
1)assigning a given email into "spam" or "non-spam" classes

2)assigning a diagnosis to a given patient as described by observed characteristics of the patient 
   (gender, blood pressure, presence or absence of certain symptoms, etc.)

some more Examples of Classification Problems
========================================
1.text categorization(e.g., spam filtering)
2.fraud detection
3.optical character recognition
4.machine vision(e.g., face detection)
5.natural-language processing(e.g., spoken language understanding)
6.market segmentation(e.g.: predict if customer will respond to promotion)
7.bioinformatics(e.g., classify proteins according to their function)


#[height, weight, shoe size]
X = [[181, 80, 44], [177, 70, 43], [160, 60, 38],
    [166, 65, 40], [190, 90, 47], [175, 64,39], [177, 70, 80]
    ]

Y = ['male','female','female','female','male','female','male']

#define variable to store decision
clf = tree.DecisionTreeClassifier()

clf = clf.fit(X,Y)

prediction = clf.predict([[190, 90, 47]])
print prediction
