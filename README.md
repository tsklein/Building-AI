# Building-AI
Building AI ideas

# Project idea: interpreting pantomime
Final project for the Building AI course

## Summary
Guess objects, emotions etc from pantomimic gestures

## Background
Helps communicating without speech.

## How is it used?
Can be used in silent environments or when no verbal speech possible. 

```
def main():
   # Observations and depending variable
   X = ["sequence of gestures illustrating object 1", "sequence of gestures illustrating emotion 1", ...]
   y = ["object 1", "emotion 1"...]

   # Split in training and validation data
   X_train, y_train, X_test, y_test = ...
   
   # Implement different methods to predict y, evaluate their performance and choose most promising one.
   
   while user_does_not_interrupt 
     # Observe and decode sequence of gestures, e.g using camera plus some code
     
     # Predict y and print result
     
main()
```

## Data sources and AI methods
To be determined

## Challenges
Limited to discrete objects, emotions as available in training data, i.e. cannot extrapolate

## What next?
Break down problem into more concrete parts and start coding

## Acknowledgments
* building AI course material
