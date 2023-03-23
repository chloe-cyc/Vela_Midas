# Vela_Midas
Midas Touch Twitter Data Project for Vela Partners Microinternship

The objective of this project was to iterate on an Investor Similarity Scoring algorithm developed previously and develop a tool which would allow for the computing of a similarity score between two investors who are active on twitter based on their likes and comments of a given users post.

Two functions were developed: __n_nearest_neighbours__ and __plot_n_nearest_neighbours__. The aim is to identify and visualise the __n__ incvestors who act in a way that is most similar to the investor of interest. The function n_nearest_neighbours calculates similarity through 4 different measures (one of which takes into account the number of likes that a given user has recieved). The plot of this function allows for observations of the similarity between investors and for the observation of whether or not investors are interacting with each other - and if they are, whether they are interacting with similar investors.
