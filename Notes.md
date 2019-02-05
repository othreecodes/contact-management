1. Setup/Installation is Windows OS Specific. Chances are the deploy environment would be a Linux variant.
2. In `views.py` , You could as well use just one ViewSet to rather than creating multiple API Views. 
3. PUT/PATCH is actually not the same thing. https://stackoverflow.com/questions/31089221/what-is-the-difference-between-put-post-and-patch But it can be overlooked.
4. Overall coding style is clean
5. No code coverage. Even tho the tests pass, its hard to tell if the code is testing the right parts. You aslo didnt test for the image upload which was an important part of this exercise.
