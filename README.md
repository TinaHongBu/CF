# Collaborative Filtering
## Background
* Active tools: Search engines
* Passive tools: Recommenders
	* Content-based: too much metadata needed
	* CFs: unaware of product attributes
		* Item-based/Model-based: Similar users -> recommendation
			- Sparcity Problem 
			- Poor Scalability
			- Purchase-based: more complementary products recommended
			- View-based: more substitute products recommended
			
			User Rating Model -> User-item matrix: 
				* Bayesian network (probablistic) 
				* clustering (classification): P(User belongs to group i)
				* rule-based
		* User-based/Memory-based: user who rated both i & j
			- Accuracy
			- Scalability
			- Performance
			* Offline 
				* Step 1 - item similarities
					* Cosine
					* Correlation
					* Adjusted-cosine
				* Step 2 - Most similar item
					* all-to-all: O(n^2) storage
					* k most similar: k << n
			* Online
				* Step 3 - Recommendatioin
					* weighted sum
					* regression
				* Step 4 - Evaluation
					* Statistical: Mean Absolute Error (MAE)
					* Decision support

## Recommender System Application
* Online retail - Amazon "people who bought X also bought Y"
* Video Streaming - Netflix "people like you liked X"
* Music - Spotify
* News - Google News

## Recommender System Influence
* Individual choices: major impact
* Sales diversity: increase/decrease. popular -> more popular

-> product inventory 
-> supply chain structures


