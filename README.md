## Springboard Capstone Project #2: U.S. Trademark Smart Search App

### Introduction
The concept of intellectual property (IP) is crucial to the goal of spurring innovation by granting special rights to inventors and creators. Trademarks, in particular, help companies distinguish themselves (and their products) from competitors. In order to avoid the expense of submitting multiple trademark applications, entrepreneurs and established businesses must conduct a search to ensure that the mark attempting to be registered is not overly similar to other already registered trademarks. Though the USPTO provides a basic search tool for their trademark database, I have decided to create a tool that uses concepts from Neural Style Transfer (NST) to analyze and compare the <i>style</i> and <i>content</i> of registered trademarks to those of the prospective design mark. The trademarks are then returned to the user in order of decreasing similarity, with respect to content and style.

### VGG Model
This project uses the VGG-19 ConvNet model developed by the Visual Geometry Group at the University of Oxford. It can be downloaded here: http://www.vlfeat.org/matconvnet/pretrained/.


Patent pending (Title: "Neural Method for Determining Image Similarity").