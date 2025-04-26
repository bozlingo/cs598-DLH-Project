#CS598- Deep Learning for Healthcare
#Final Report: Reproducing Alzheimer’s Disease Classification

Tim Crosling (tgc3@illinois.edu)
Bhavuk Jain (bhavukj2@illinois.edu)
 
Reproduction of Paper: “Back to the basics with inclusion of clinical domain knowledge- A simple, scalable and effective model of Alzheimer’s Disease classification”; Bruningk S., Hensel F., Lukas L., Kuijs M., Jutzeler C., Rieck B.; Proceedings of Machine Learning Research; 2021

This report details the approach we took to reproduce the paper along with an evaluation of the results of our reproduced code. This also includes an extension to assess three different pipeline model approaches: 1) CNN only, 2) CNN with GNN, 3) CNN with GNN including persistent homography features. Finally, our reproduction also extends the original concept by wrapping our code in a pyHealth code hosted on gitHub and requested to fold into the core pyHealth library. We reach similar conclusions to the paper, notably that CNN with GNN is sufficient to identify and classify Alzheimer’s Disease on standard high resolution MRI images without the need for more computationally intensive processing such as Topological Data Analysis (TDA).

Repository Contents:
- 4 Minute Video Overview
- Final Report pdf
- Notebook code with final execution run
- ChatGPT conversation used for reproduction
