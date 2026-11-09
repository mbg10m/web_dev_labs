This program uses a github repo as a source for names of cities and states in the United States of America.
It uses JS fucntions in order to filter the array of names and find the ones that match with the user input.

Things I learned:
The notion of asynchronous javasScript is something that we did and learned in class. But doing the thing myself along the tutorial gave me a better understanding of the concept.
In the lines:
fetch(endpoint)
.then((blob) => blob.json())
.then((data) => cities.push(...data));
asynchronous javascript is used to make a request to the server (the url assignment to "endpoint") and then determines what to do with that repsonse via the .then() notations.

Something new to me is the ".json()" method. This method reads an entire HTTP response and then converts it into a useable JavaScript object or array that is easier to read than the original response.

Another new thing I learned in the built-in JS object Regex, which stands for Regular Expression. It mainly serves two purposes in filtering/searching for the matching user input in the data set. The Regex object enables the qurey to not be case sensitive when filtering the array data set. Meaning "A" and "a" both stand for the same thing, the search function is case insensitive. The second use case of the Regex object is to command the findMatch() function to not stop at the first match but continue throughout the entire string/array and then return all the resulting matches.
