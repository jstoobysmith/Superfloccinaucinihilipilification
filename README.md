# Superﬂoccinaucinihilipiliﬁcation

This is a code to generate semi-simple extensions of given Lie algebras & representation combinations. It was developed by: 
Andrew Gomes, Maximillian Ruhdorfer, and Joseph Tooby-Smith

### Running the code.

Detailed instructions on how to use our code are given in the corresponding paper.

To summarize: 
- Download the file SuperFlocci.m, and import it into a Mathematica notebook using:
  
`Import["SuperFlocci.m"];`
- Call the SuperFlocci using, e.g. (for the 1 gen SM)
  
`out = SuperFlocci[{A1,A2,U1}, {{1,1,0,1},{0,0,1,-4},{0,0,1,2},{1,0,0,-3},{0,0,0,6},{0,0,0,0}}];`
- See the output using
  
`FlocciOutput[out];`
