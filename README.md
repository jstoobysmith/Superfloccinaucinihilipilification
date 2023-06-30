# Superﬂoccinaucinihilipiliﬁcation

This is a code to generate semi-simple extensions of given Lie algebras & representation combinations. It was developed by: 
Andrew Gomes, Maximillian Ruhdorfer, and Joseph Tooby-Smith.

If you use this code please cite:

- A.Gomes, M.Ruhdorfer and J.Tooby-Smith, _Superfloccinaucinihilipilification: Semisimple unifications of any gauge theory_, [arXiv:2306.16439](https://arxiv.org/abs/2306.16439).

### Running the code.

Detailed instructions on how to use our code are given in the corresponding paper.

To summarize: 
- Download the file SuperFlocci.m, place it in the same directory as your Mathematica notebook and import it using:

`SetDirectory[NotebookDirectory[]];`

`Import["SuperFlocci.m"];`

- Call the SuperFlocci using, e.g. (for the 1 gen SM)
  
`out = SuperFlocci[{A1,A2,U1}, {{1,1,0,1},{0,0,1,-4},{0,0,1,2},{1,0,0,-3},{0,0,0,6},{0,0,0,0}}];`
- See the output using
  
`FlocciOutput[out];`

### Note about compilers

Our program uses compiled C-code to run faster. Some operating systems do not come with a built-in C compiler (namely Windows). In these cases, the code will still run, but with warnings and will be slower. You may install your own compiler. See
  https://reference.wolfram.com/language/CCompilerDriver/tutorial/SpecificCompilers.html
for more details.
