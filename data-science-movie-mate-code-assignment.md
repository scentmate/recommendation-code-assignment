# MovieMate Data Science Code Assignment

In addition to the task explanation on the deck this document puts emphasis on the technical requirements of the first
two tasks:

* _Build a recommendation engine_
* _Expose the algorithm via a web API_

This document specifies the requirements of the `moviemate` module from an architectural and coding guideline
perspective. However, it does not limit the modeling approaches at all.

## Overall guidelines

We ask you to follow the listed coding principles:

* Add docstrings and type hints to all functions
* Write log messages throughout your code
* Make sure that your python code follows the PEP8 style guidelines
* Add a `README.md` file to explain how to run the code and spin up the REST API locally
* When developing your code, please use git to track your changes

## `moviemate`

Basic requirements of the `moviemate` module:

* The recommendation engine should be encapsulated into the `MovieMateRecommender` class.
    + The method `query` should be the access point to the recommendation engine.
        - This method should return recommendations based on the provided input.
        - It is completely up to you which input and output types to use (lists, dictionaries, etc.).
    + Feel free to add more properties and methods to this class

* The remaining implementations and architectural decisions are completely up to you. Feel free to add more files, classes
and modules.

* The recommendation engine should be exposed on a REST API GET endpoint.

## Submission

Please submit a zip archive of the `movie-mate` folder (exclude the input data from the zip file).
