# AR MemoryPalace for iOS 
Created by Gareth George and Dana Nguyen

In this project we provide our take on an augmented reality memory palace learning tool built using the great ARKit and SceneKit libraries provided on iOS. 
Our project is runnable on any iOS device with support for these libraries (iPhone X and up).

## Background

Memory palaces (sometimes referred to as the method of loci) have an ancient history going back to the time of Roman and Greek orators. 

Memory palaces are a memorization strategy which enhances the recall of information by associating it with objects in a familar spatial environment. Once these associations have been trained, recallation of the information is enhanced as the user can visually imagine a journey from the environment and recall the locations where they mentally placed the information.

Additionally, studies such as 'Virtual Memory Palaces: Immersion Aids Recall' (by Krokos et. al) have established when virtual (VR) memory palaces are used in training they can even enhance the quality of recollection -- by their results training with head mounted displays improved recollection by ~9%.

We attempt to extend these principles into augmented reality using an AR app to help users attach material to memorize to physical objects, study these mappings, and test themselves on the content.

## Running the project
**The project has only been tested on iPhone iOS version 13.4+**

1. Open 'MemoryPalace.xcworkspace' in Xcode
2. Build the project by clicking the 'play' button. 
    * If build does not work, try to go into build settings > signing and capabilities, and change the team and build identifier

## Project Demo Video

TODO: insert demo video links here

## Engineering Challenges

### World Tracking Challenges & Solutions

ARKit provides us with out of the box high quality world tracking, however, 
