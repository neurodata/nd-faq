# Current Projects

## Drosophila larva connectome
### Primary people: 
*@BPedigo*

### Description:
We are collaborating with Dr. Marta Zlatic and Dr. Albert Cardona’s groups to analyze the first 
[nanoscale connectome](https://www.nature.com/articles/d41586-019-02208-0) of the
*Drosophila* larva brain. The *Drosophila* larva is an important model organism in neuroscience.
Our collaborators have spent years mapping neuron-to-neuron connections for the entire
brain of this organism, first using electron microscopy to image the entire nervous system, 
and then manually annotating neurons and synapses in this image volume to generate the synaptic wiring diagram.

We are now assisting in the analysis of this connectome, which we can model as a network (graph).
We can characterize this network using various statistical models of graphs, many of which have been 
developed and studied over the last 10-15 years here at Hopkins. We are also working on questions like
- Can we discover new "cell types" defined on the basis of connectivity using techniques like clustering on the graph?
- How can we quantify the role that individual neurons play in the pathway from sensory input to motor output?
- How do different types of synapses (such as axon to axon vs. axon to dendrite) play different roles in the graph,
and how do they affect the above two questions? 

## GraSPy
### Primary people:
*@BPedigo*, *@j1c*

### Description: 
Starting last year in [Neuro Data Design](https://neurodatadesign.github.io/) (Jovo's class), we developed a
Python package for doing statistical analysis on network data. This includes features such as fitting statistical 
models to graphs or populations of graphs, statistical hypothesis testing for networks, and more recently, graph 
matching.

### Publications:
[GraSPy: Graph Statistics in Python](http://www.jmlr.org/papers/volume20/19-490/19-490.pdf)

## Lifelong Learning
### Primary people:
*@rmehta004*, *@hhelm10*

### Description:
Our lab is partially funded by the Lifelong Learning Machines (L2M) DARPA program. The goal of L2M is to 1) understand the biological mechanisms that allow humans to generalize knowledge well/quickly and to 2) develop novel algorithmic approaches to "modern" machine learning problems such as transfer-, multi-, continual-, and lifelong- learning. Our research is exclusively related to 2). We have developed forest-based algorithms that are interpretable and generalizable to other base learning methods.

We are also interested in understanding and developing mathematical/statistical generalizations of learning theory / decision theory that include "modern" machine learning problems and that are strict generalizations of the theories of Valiant/Vapnik and Wald. 

Some questions that we are excited to answer:
- What does it mean to "transfer" knowledge? How do I measure an algorithm's ability to "transfer"?
- When should I expect to be able to "transfer" knowledge? How does a particular algorithm "transfer" knowledge? 
- What are desireable properties of transfer-, multi-, continual-, and lifelong- learning algorithms?

## Mouselight
### Primary people:
*@tathey1*, *@vikramc*

### Description:
HHMI Janelia has recently developed a two-photon microscopy technique that can resolve mammalian neurons that project across the whole brain! (https://www.ncbi.nlm.nih.gov/pubmed/31495573). However, the process of tracing(/segmenting) the neurons remains a bottleneck. In a collaboration between JHU and Janelia, we are trying to accelerate this process using classic image processing, dynamic programming, and cloud computing.