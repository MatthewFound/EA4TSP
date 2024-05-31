# EA4TSP
Repository contains functions for a basic Evolutionary Algorithm (EA) to solve the Travelling Salesman Problem (TSP).

I don't provide initial distance matrix manipulation code or a TSP dataset here as these are likely unique to each induvidual problem. TSP datasets are readily availible on sites like Kaggle or in other GitHub repositories. For example, in my consideration I used these functions to optimise a 54-vertex and 14-vertex problem. To use these functions without alteration you must create a distance matrix in a compatible format. The distance matrix must be a pandas dataframe where the entry for each index-row pair represents the distance between respective cities. That is, the entry in index 2, row 5 is the distance between city 2 and city 5. An easy sanity check is to ensure that the diagonal of the distance matrix is populated with zeros as this would correspond to the distance between a city and itself. Moreover the entry for index 2, row 5 should be the same as the entry for index 5, row 2 and so on... 
