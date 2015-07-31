# P1-Movie-Trailer-Website
by Jeff Chiu, in fulfillment of Udacity's Full-Stack Web Developer Nanodegree

About

This is project one as the part of full stack web developer nanodegree at [Udacity](https://www.udacity.com/course/nd004).
I will write **server-side code** to store a list of my favorite movies, including:
* box art imagery
* movie trailer URL
I will then serve this data as a web page allowing visitors to review their movies and watch the trailers.


How to run
To run the script, clone this repository directory and run fresh_tomatoes.py. You can view the page by opening fresh_tomatoes.html.

Steps that I did:
Download the file fresh_tomatoes.py which contains the open_movies_page() function that will take in your list of movies and generate an HTML file including this content, producing a website to showcase your favorite movies.
Your task is to write a movie class in media.py. To do this, think about what the properties of a movie are that need to be encapsulated in a movie object such as movie titles, box art, poster images, and movie trailer URLs. Look at what open_movies_page() does with a list of movie objects for hints on how to design your movie class.
Next you’ll want to write a constructor for the movie class so that you can create instances of movie.
You can now create a list of these movie objects in entertainment_center.py by calling the constructor media.Movie() to instantiate movie objects. You’ve given movies their own custom data structure by defining the movie class and constructor, and now these objects can be stored in a list data structure. This list of movies is what the open_movies_page() function needs as input in order to build the HTML file, so you can display your website.
