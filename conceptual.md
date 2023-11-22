### Conceptual Exercise

Answer the following questions below:

- What are important differences between Python and JavaScript?
*Python has things like tuples and the dictionaries in python have more methods for accessing key-value pairs than in JS
*Python reads more like English.
*Python is a pure OOP Language.

- Given a dictionary like ``{"a": 1, "b": 2}``: , list two ways you
  can try to get a missing key (like "c") *without* your programming
  crashing.
  *if dict was named "dic" you could attempt accessing it with "print(dic['c'])"

- What is a unit test?
*A unit test is a test that typically only focuses on testing a single function.

- What is an integration test?
*An integration test is an all encompassing test that test the entire application.

- What is the role of web application framework, like Flask?
*flask creates a server that serves up call and responses.


- You can pass information to Flask either as a parameter in a route URL
  (like '/foods/pretzel') or using a URL query param (like
  'foods?type=pretzel'). How might you choose which one is a better fit
  for an application?
  *There isn't an exact better way to do this but it depends on the situation. /foods/pretzel would usually be predefined or categorical as /foods/X could be any possible food. Foods?Type is probably more for search based routing.

- How do you collect data from a URL placeholder parameter using Flask?
*request.args

- How do you collect data from the query string using Flask?
*request.url 

- How do you collect data from the body of the request using Flask?
* request.arg.get

- What is a cookie and what kinds of things are they commonly used for?
*A cookie is a key-value pair, useful for storing information about the user/whoever is visiting your site. Such as login information and settings.

- What is the session object in Flask?
*A session is similar to a cookie, as it stores information on a user\computer that is carried over during the course of a browsers life. This can help keep track of constantly updating variables that will be referencable as long as the browser\window remain open. Not affected by refreshes.

- What does Flask's `jsonify()` do?
*jsonify will return flask variables\data that need to be turned into the JSON format for frontend API's to consume
