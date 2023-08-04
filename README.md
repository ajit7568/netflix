# netflix
https://ajit7568.github.io/netflix/?authuser=3
index.html
<!DOCTYPE html>
<html>
  <head>
    <!-- The head section contains metadata about the document, including character encoding and viewport settings. -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!-- The link tag is used to include an external CSS file called "style.css" to apply styles to the document. -->
 <link href="style.css" rel="stylesheet"/>  

    <!-- The title tag sets the title of the document, which appears in the browser's title bar or tab. -->
  <title>Netflix | India</title>
  </head>
  <body oncontextmenu="return false;">
    <!-- The body tag represents the content of the HTML document visible to the user. The oncontextmenu attribute is used to disable right-click context menus on the page. -->
    <div id="shadow">
      <!-- The div element is a container that groups content together and allows applying styles or JavaScript to specific sections. The id attribute sets the unique identifier for this div. -->
      <div id="heading">
        <!-- Another div for the header section with the Netflix logo and buttons. -->
        <div id="image">
          <!-- The img tag is used to embed an image in the document. The src attribute specifies the image URL, and the width and height attributes set the image dimensions. -->
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/08/Netflix_2015_logo.svg/2560px-Netflix_2015_logo.svg.png"
            width="150"
            height="50"
          />
        </div>
        <div id="buttons">
          <!-- The button element creates a clickable button. The id attribute sets a unique identifier for the buttons. -->
          <button id="signin">Sign In</button>&nbsp;&nbsp;&nbsp;
          <button id="signin">Register</button>
        </div>
      </div>

 <div id="main">
        <!-- The main section with a heading and paragraphs. -->
   <h1>Unlimited movies, TV shows and more.</h1>
        <!-- The h1 tag represents a top-level heading. -->
 <p id="p1">Watch anywhere. Cancel anytime.</p>
        <!-- The p tag represents a paragraph. The id attribute sets a unique identifier for this paragraph. -->
 <p id="p2">
          Ready to watch? Enter your email to create or restart your membership.
  </p>
      </div>
    </div>
  </body>
</html>
 /* Set the default margin for the body to 0 and use a background image from the given URL */
body {
  margin: 0;
  background: url("https://assets.nflxext.com/ffe/siteui/vlv3/8f12b4f0-a894-4d5b-9c36-5ba391c63fbe/44355e66-dbf8-4dd8-ba6b-8e9e32ec6abd/IN-en-20230320-popsignuptwoweeks-perspective_alpha_website_large.jpg");
}

/* Styling for the header section */
#heading {
  height: 20%; /* Set the height of the header section to 20% of the viewport height */
  display: flex; /* Use flexbox to arrange the child elements horizontally */
}

/* Styling for h1 headings */
h1 {
  font-size: 55px; /* Set the font size of h1 headings to 55px */
  margin: 0; /* Remove default margin for h1 elements */
}

/* Styling for the shadow container */
#shadow {
  background: rgba(0, 0, 0, 0.7); /* Use a semi-transparent black background */
  height: 100vh; /* Set the height of the shadow container to 100% of the viewport height */
}

/* Styling for the image container */
#image {
  width: 40%; /* Set the width of the image container to 40% */
  display: flex; /* Use flexbox to horizontally center its child elements */
  justify-content: center; /* Center the child elements horizontally */
  padding: 30px; /* Add padding around the content inside the image container */
}

/* Styling for the buttons container */
#buttons {
  padding: 30px; /* Add padding around the content inside the buttons container */
  width: 60%; /* Set the width of the buttons container to 60% */
  text-align: right; /* Align the content inside the buttons container to the right */
}

/* Styling for the main content section */
#main {
  display: flex; /* Use flexbox to arrange the child elements vertically */
  flex-direction: column; /* Arrange the child elements in a column */
  justify-content: center; /* Center the child elements vertically */
  align-items: center; /* Center the child elements horizontally */
  color: white; /* Set the text color to white */
  height: 80%; /* Set the height of the main content section to 80% of the viewport height */
}

/* Styling for the "Sign In" and "Register" buttons */
 signin {
  background: red; /* Set the background color of the buttons to red */
  padding: 8px 14px; /* Add padding inside the buttons */
  border: none; /* Remove the button border */
  color: white; /* Set the text color to white */
  font-size: 15px; /* Set the font size of the button text to 15px */
  border-radius: 5px; /* Add rounded corners to the buttons */
  font-weight: bold; /* Set the font weight to bold */
}

/* Styling for paragraphs */
p {
  margin: 13px; /* Set margin around paragraphs */
  font-weight: 400; /* Set the font weight of paragraphs to 400 (normal) */
}

/* Styling for the paragraph with id "p1" */
p1 {
  font-size: 28px; /* Set the font size of the paragraph with id "p1" to 28px */
}

/* Styling for the paragraph with id "p2" */
#p2 {
  font-size: 23px; /* Set the font size of the paragraph with id "p2" to 23px */
}


