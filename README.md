<h1>Functional Record Script</h1>

Improves video game VO record session by allowing the Director to effortlessly navigate the VO record script and have access to any edited audio files previously recorded. The HTML script generator Python file will need to be executed each time when new audio files have become available.

The HTML script generate Python file does the following:

- Converts an Excel files to an HTML table
- Checks a directory for any audio files that match the audio file name within a column of the script
- Adds the appropriate audio file to the corresponding cloumn
- Creates a play / stop button for the audio file
- Adds pagination, sort, and sreach functionality

The HTML file references the CSS and JS scripts within this repo.

