Data consists of a Spoitfy artist playlist co-occurence graph in the US. The nodes in the graph represents individual artists. The edges represents artists that have appearted together in a playist. The weight represents how many times they have appeared together. analysis.ipynb contains all the visualizations and analysis done on the graph. network_init.ipynb contains the initialization code for converting the raw csv data into a graphml file. The 30testvisualization.gephi file is a Gephi graph that shows a visualization of the graph using Gephi's modularity partition. 
1. Only analysis.ipynb is needed to be ran to see the analyis of the graph again.
2. The graphml files are all already generated in the graphs folder.
3. Only run network_init.ipynb to generate a new set of graphml files. 

artists_graph_connected_100.graphml contains the graph for the data sampled from 100 playlists, while artists_graph_connected_30.graphml contains the graph for 30 playlists. For all the analysis, the 30 sample size is used.
