# Make your AI Algorithm Blueprint

This is an ongoing visualization project where the goal is to allow general people to understand and design the basic prototype of an AI algorithm. This is similar to generating a blueprint for the AI architecture from scratch. This will ultimately allow users to play around with the building blocks of the AI architecture and see workflow with numbers and matrices in Prof. Tom Yeh’s AI-by-Hand manner.

***
**The target users** of this tool are ones -
- Who do not have coding skill knowledge, but has the idea behind it and wants to build architectures
- Who wants to deep dive into the AI black box and learn the underlying mechanism.

The platform I used here is Excel – because it is widely used by mass audiences and very easy to follow. In most of the cases people do not need to do a cold start in learning MS Excel, since most of them are already familiar with this from their student life.

To automate, I used **MS Excel’s Office Script** (based on TypeScript). The use does not require learning Office Script. In short: users will have to download a copy of the file and provide building blocks (e.g. Inputs, Linear Layer, ReLU, etc.) in a table in it and then hit the “Run” button. In another sheet, the whole architecture will be unboxed using numbers and matrices.

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
### Multi-layer Perceptron
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
 
***
## How to use:
- Download a copy of the Excel file from this repository. Note: there are two separate Excel files for Attention and MLP.
- Add/ change the input, operations and output in the Architect sheet. Follow the example architecture provided.
- Hit run button
- A sheet named Blueprint will be generated with the visualization of the workflow in AI-by-Hand format

***
<img width="796" height="657" alt="image" src="https://github.com/user-attachments/assets/a6405c0b-a71f-44b8-b0df-3abca92338de" />

<img width="614" height="233" alt="image" src="https://github.com/user-attachments/assets/d05e7853-85b2-4eb5-8919-af151a07ef01" />

<img width="386" height="689" alt="image" src="https://github.com/user-attachments/assets/f8064913-de24-4dfe-86fe-2a3798c8afdf" />




