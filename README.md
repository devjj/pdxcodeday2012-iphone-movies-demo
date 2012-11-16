Portland CodeDay 2012 iPhone Demo
=================================

1. Clone the repo.
2. Visit the [Rotten Tomatoes API page](http://developer.rottentomatoes.com/docs) and register for an API key.
3. Edit the `MoviesViewController.m` file and find the following line in the `refreshMovies` method:

	 ```objective-c
	 NSMutableURLRequest *request = [NSMutableURLRequest requestWithURL:[NSURL URLWithString:@"http://api.rottentomatoes.com/api/public/v1.0/lists/movies/box_office.json?apikey=YOUR_API_KEY"]];
	 ```

	 Replace `YOUR_API_KEY` with your API key.

4. Run it.