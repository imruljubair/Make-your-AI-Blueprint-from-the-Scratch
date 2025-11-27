# Make your AI Algorithm Blueprint

This project is an ongoing effort to create visualizations that help anyone understand and design the basic prototype of an AI algorithm. It works like generating a blueprint for an AI architecture from scratch, allowing users to experiment with the building blocks of the system and observe the workflow through numbers and matrices in Prof. Tom Yeh’s “AI-by-Hand” style.

***
This tool is designed for:
+ People who don’t have coding skills but understand AI concepts and want to design architectures.
+ Learners who want to look inside the “AI black box” and explore the underlying mechanisms.

I chose Excel as the platform because it’s widely used, accessible, and familiar to most people—often requiring no new learning curve. Many users have already worked with Excel at some point in their academic or professional life.

To enable automation, the project uses MS Excel Office Scripts (TypeScript-based). Users do not need to learn Office Script. All they need to do is download the file, specify the building blocks (e.g., Input, Linear Layer, ReLU, etc.) in a table, and press the Run button. Another sheet will then automatically “unbox” the entire architecture using numbers and matrices.

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
## Example - 1
<img width="600" height="450" alt="image" src="https://github.com/user-attachments/assets/a6405c0b-a71f-44b8-b0df-3abca92338de" />
<br>
<img width="614" height="233" alt="image" src="https://github.com/user-attachments/assets/d05e7853-85b2-4eb5-8919-af151a07ef01" />
<br>
<img width="386" height="689" alt="image" src="https://github.com/user-attachments/assets/f8064913-de24-4dfe-86fe-2a3798c8afdf" />
 
***
## Example 2
<img width="666" height="320" alt="image" src="https://github.com/user-attachments/assets/1af20fa4-8f39-4b1a-8ed7-20c48951c71c" />
<br>
<img width="526" height="567" alt="image" src="https://github.com/user-attachments/assets/03df7230-4b15-465a-878f-b0b4aed1397e" />






