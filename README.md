# sound_cluster
 
Download data from [here](https://pennstateoffice365-my.sharepoint.com/:u:/g/personal/wxc272_psu_edu/Efntma-N0HNJhwuV136ns-sBqdz1NNifcd3IuACas51Stg?e=XHqell) and put it under `sound_cluster` folder.

Run `kmean_cluster_on_frequency_domain.ipynb`, the cluster result will be saved in `result` folder (e.g., if we want to cluster into 3 clusters, then it will create folders `cluster_0`, `cluster_1`, and `cluster_2` and copy the audio file inside it). 

The cluster results are summarized in `cluster_result.txt`, the filenames are sorted by the distance to its cluster centor (how representative these samples). If you go to the end of `kmean_cluster_on_frequency_domain.ipynb`, you can also play these audios in the jupyter notebook.
