# video-retrieval-base-on-scene-graph
reference paper list:
	scene graph
	1.
 
 Birpartite embedding:
 1. BiANE: Bipartite Attributed Network Embedding https://dl.acm.org/doi/pdf/10.1145/3397271.3401068

Dataset:
Charades-STA:

next step:
1. scene graph embedding
2. timestamp normalization
3. query embedding
4. ....

sg folder:(sentences bert)
videoname.npz:
	objects_embeddings:[objects_len, 384]
 	relations_embeddings:[relations_len,384]
  	adj_matrix:[objects_len,relations_len]

annotationssg_temporal_train_1.pkl: the scene graphs of all train videos, every video has one sg.

52.DSG-DETR2/hj_test.ipynb: the preprocessing code of sg and it's npz file.
