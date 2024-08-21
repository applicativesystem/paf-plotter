# paf-graphs-plotter

- BUG check ans till some more to code for the final release.
- a paf formatter and plotter for the graph analysis and see the alignment of the miniasm and it uses faster approach for the analysis of the paf alignments and also outputs and extracts the corresponding paf alignments for the graphs.
- use the miniasm for the alignment and generation of the paf formats and then plot the paf alignments with this graph utility.
- A miniasm description of the paf is given here: [miniasm](https://github.com/lh3/miniasm/blob/master/PAF.md).
- I implemented in a way that it is reading the entire PAF alignments into a single dataframe with a single loop keeping the complexity to O(n).

```
def pafplotter(paffile = None, \
                    querychr = None, \
                        mapping = None, \
                                lengthplot = "FALSE", \
                                        catplot = "FALSE", \
                                                    mapping_quality_plot = "FALSE", \
                                                                scatterplot = "FALSE")
```

Gaurav \
Academic Staff Member \
Bioinformatics \
Institute for Biochemistry and Biology \
University of Potsdam \
Potsdam,Germany 
