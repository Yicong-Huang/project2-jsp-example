## CS 122B Project 2 JSP example

This example shows how frontend and backend are separated by implementing a star list page.

### To run this example: 
1. clone this repository using `git clone https://github.com/UCI-Chenli-teaching/project2-jsp-example.git`
2. open Eclipse -> File -> import -> under "Maven" -> "Existing Maven Projects" -> Click "Finish".
3. For "Root Directory", click "Browse" and select this repository's folder. Click "Finish".
4. In "Java Resources" folder, open `index.jsp`. Change the mysql username and password and make sure you have the `moviedb` database.
5. You can run this project on Tomcat now.

### Brief Explanation
`index.jsp` dynamically generates the html page with Java API. It is requested as a static resource, rather than a servlet sample we have seen before.
The .jsp file is requested directly.
