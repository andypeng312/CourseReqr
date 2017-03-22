# README
## Description of Project
CourseReqr is a submission for TartanHacks, a hackathon run by ScottyLabs at
Carnegie Mellon University. The project is a collaboration between Andy Peng, 
Leanna Pancoast, Charles Chong, and Kevin Lau and was completed in a span of
24 hours. The project won the $150 Scotty Labs Campus Data Award.

The final product can be viewed by running the `index.html` file.

The project's goal is to create an aesthetically-pleasing and intuitive way of
visualizing a "route" of courses one can take. Usually courses on the catalog
will list pre-requisites however, it is not as easy to see what other courses
you are eligible for once you take a course. CourseReqr maps all the courses in
CMU's Schedule of Courses into a beautiful graph that provides a great tool for
planning courses.

The screenshot folder displays images of our final product. In the
visualization, the selected class is an orange bubble, the pre-requisite
classes are red bubbles, and the classes that become available after one takes
the selected class are blue bubbles. If you indicated that you have taken a
class, that is marked by an orange outline.

The UI elements in this project were created using Flat UI, a user interface
kit built on Bootstrap and available at http://designmodo.github.io/Flat-UI/.
The data visualization was created using D3.js, a JavaScript library available
at https://d3js.org/. The data was scraped from the Carnegie Mellon University
Schedule of Courses and compiled into a json file using a Python script that is
not included.

## Contents
* **`CourseReqr`**- contains the files and code for the project; final product
can be viewed by running the `index.html` file
* **`hackathon_ideas.txt`**- a brainstorming list of ideas we had for the
hackathon
* **`Screenshots`**- contains images of the site
---
**Technologies used:** HTML, CSS, JavaScript, Python, Java, Bootstrap, D3.js  
**Estimated Lines of Code:** 1200

![](/Screenshots/screenshot2.png)