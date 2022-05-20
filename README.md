# Matrix Task
## Algorithm
1) First index chooses which matrix to pick, so at first we skip the unwanted i * (m * p) elements where i is the number of matrix we want
2) Second index chooses the proper row in the matrix we chose, so we skip all the unwanted rows until we reach the one we want j * (p) where j is the row
3) Third index indicates which column in the row that we want, so we skip all the unwanted columns so we use (k)
4) So at the end the vector index will look like = i * (k * p) + j * (p) + k
