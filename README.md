This project is a clone of Google's homepage.

I only referenced color values from developers tools. Everything else was found by trial and error and Googling.

I'm mostly very pleased with how it turned out. My biggest disappointment is that I couldn't figure out how to add the little magnifying glass and microphone to the search bar. I chose to directly apply CSS to the search form, which may be the reason I couldn't get the magnifying glass and microphone to behave as child elements and have an absolute position relative to that container. 

I have two big takeaways from this project:

    1) using 'overflow: hidden;' on the navigation bar container to force the bar to span the entire screen. This kept the logo in the center of the screen regardless of window size. 

    2) using 'display: flex;' on the search buttons to keep them on the same line and centered below the search form.