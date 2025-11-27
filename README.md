# Make your AI Algorithm Blueprint

This is an ongoing visualization project where the goal is to allow general people to understand and design the basic prototype of an AI algorithm. This is similar to generating a blueprint for the AI architecture from scratch. This will ultimately allow users to play around with the building blocks of the AI architecture and see workflow with numbers and matrices in Prof. Tom Yeh’s AI-by-Hand manner.

***
The target user of this tool are ones -
- Who do not have coding skill knowledge, but has the idea behind it and wants to build architectures
- Who wants to deep dive into the AI black box and learn the underlying mechanism.

The platform I used here is Excel – because it is widely used by mass audiences and very easy to follow. In most of the cases people do not need to do a cold start in learning MS Excel, since most of them are already familiar with this from their student life.

To automate, I used MS Excel’s Office Script (based on TypeScript). The use does not require learning Office Script. In short: users will have to download a copy of the file and provide building blocks (e.g. Inputs, Linear Layer, ReLU, etc.) in a table in it and then hit the “Run” button. In another sheet, the whole architecture will be unboxed using numbers and matrices.

***
## Current version’s feature:
### Attention:
- User can play with
  + Input sequence
  + Positional Encoding
  + Normalization
  + Linear projection of Q K V with the change of dimension
  + Matrix multiplication
  + Softmax
  + Layer Normalization
- User will also get to see
  + Description of each block as comments to the cells
  + Equivalent pytorch code for each building blocks
## Multi-layer Perceptron
- A dataset “tinyDigits” is provided in a sheet which
  + Contains pixel values of synthetic digits from 0 to 9
  + Allows users to play around with augmentations (flip, shift, noise, etc.)
- User can experiment with
  + Batch
  + Flatten
  + Linear layer and change of dimensions
  + ReLU
  + Softmax
  + Layer Normalization

