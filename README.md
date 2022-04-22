# Recommend
ETHAmsterdam hackathon | Lens protocol-based social networks centered around recommendations
Below is an overview of the idea, with two examples of use-cases. 

Idea: 

	• Build social network platforms centered around recommendations, based on your 'social graph'.
	• The overall structure of these platforms would be similar:
	• Input: your 'Social Graph', provided by the 'Lens Protocol'. This social graph includes:
		○ The connections you follow (or your 'friends' in a Facebook-like model)
		○ The 'proximity' to each individual based on key metrics coming from other Lens Protocol-based social apps
			- e.g. number of messages you have exchanged on a messaging app 
			- e.g., based on the number of friends in common
			
	• Output: recommendations based on your what your social graph likes.
	• In the middle: [TBD, BUT LOT OF FUN GUARANTEED!]
	
Two examples of platforms we could build, based on this model:

	• Notes. There are many more possibilities, just think about all the instances where you would appreciate recommendations from your network/friends.
		
	• Example 1: TripAdvisor vWeb3.0
		○ Context:
			- You are going abroad on holidays (or for a conference, or just moving abroad long-term)
		○ Problem:
			- You search for cool spots in that new city (restaurants, accomodation, leisure activities, etc.)
				□ Painpoint 1: This takes  time, mainly bc the information is scattered across the web and books, and often not up-to-date.
				□ Painpoint 2: Online reviews are given by random people who may have very different preferences than you (YES WE LOOK AT YOU TRIPADVISOR AND GOOGLE REVIEWS)
				□ Painpoint 3: And these reviews can be faked - we need Sybil resistance.
		○ Solution:
			- You get recommendations based on what places your social graph liked
			- Preliminary ideas for hackathon MVP:
				□ Map of a city, with dots that represent the cool places (restaurant, bars, gallery, etc.)
				□ Size of the dot is given by some recommendation system, based on some  (complex) math formula with your social graph and its activity as input
				□ We can add some filters, such as:
					- Type of place ('what's the best rooftop in town?')
					- Demographics (only my Brookkly friends bc they are hipsters, only my 60+ friends bc I am with my grandma, etc.)
					
	• Example 2: Netflix vWeb3.0
		○ Context:
			- You want to watch a movie (or read a book)
		○ Problem it solves: 
			- You browse the recommendations from Netflix/ other similar platforms
				□ Painpoint 1: Cold start problem: Netflix does not know you in the beginning, so recommendations are pure s***
				□ Painpoint 2: Even after watching multiple movies, recommendations are still based solely on your experience, hence still kind of s***
				□ Painpoint 3: There is nothing social about this experience. I need to ask friends via messenger, then watch the movie, then talk separately with them on  messenger to tell how cool the movie they recommended was. My messages on messenger do not feed back to the recommendation system.
		○ Solution:
			- You get recommendations based on what movies your social graph likes
			- Preliminary ideas for hackathon MVP:
				□ We simulate a social graphs watching movies
				□ We have a new joiner on the platform, and we show the movies recommended
				□ Filter: again we can add some
				
	
	

