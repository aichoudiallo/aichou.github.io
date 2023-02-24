# Student Bio Page

In this activity, you will create a simple HTML page to serve as a personal bio.

## Instructions

* Create a simple bio page for yourself by using the following HTML elements:

  * A header that will store your name inside of it.

  * An image that will act as a stand-in for your picture, with an `alt` attribute that provides a basic description of the image.

  * Two paragraphs that will have text describing who you are.

  * An unordered list of links to your social media pages.

  * A table that will contain three columns and some data on your favorite movies, songs, books, or activities.

## Hint

* Placeholder images can be found at [picsum.photos](https://picsum.photos/), and placeholder text can be found at [lipsum.com](http://www.lipsum.com/). Try to get the entire page working before diving into more specific text and images.

## Bonus

* Look into how one might go about linking one custom-made HTML page to another. Once you have found out how, try creating a link from the bio page you have just created to one of the pages you created last class.

- - -

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
<!DOCTYPE html>
<html>
  <head>
    <title>My Bio Page</title>
  </head>
  <body>
    <header>
      <h1>John Doe</h1>
    </header>
    <img src="https://picsum.photos/200" alt="A placeholder image of a person" />
    <p>Hi, my name is John Doe and I'm a student at XYZ University. I'm majoring in Computer Science and I love coding.</p>
    <p>In my free time, I enjoy playing basketball and reading books on technology and entrepreneurship.</p>
    <ul>
      <li><a href="https://www.linkedin.com/in/john-doe/">LinkedIn</a></li>
      <li><a href="https://twitter.com/johndoe">Twitter</a></li>
      <li><a href="https://www.instagram.com/johndoe/">Instagram</a></li>
    </ul>
    <table>
      <thead>
        <tr>
          <th>Category</th>
          <th>Name</th>
          <th>Rating</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Movies</td>
          <td>The Godfather</td>
          <td>10/10</td>
        </tr>
        <tr>
          <td>Songs</td>
          <td>Bohemian Rhapsody</td>
          <td>9/10</td>
        </tr>
        <tr>
          <td>Books</td>
          <td>The Lean Startup</td>
          <td>8/10</td>
        </tr>
        <tr>
          <td>Activities</td>
          <td>Basketball</td>
          <td>9/10</td>
        </tr>
      </tbody>
    </table>
    <a href="path/to/another/page.html">Link to another page</a>
  </body>
</html>


Regenerate response

