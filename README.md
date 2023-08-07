Google Slides Generator from Google Sheets
This project is a Google Apps Script that generates a Google Slides presentation from data in a Google Sheets spreadsheet. It also fetches relevant images from Pixabay based on keywords in the spreadsheet and adds them to the slides.

Features
Fetches data from a Google Sheets spreadsheet.
Generates a Google Slides presentation based on the data.
Fetches relevant images from Pixabay based on keywords in the spreadsheet.
Adds the images to the slides.
How to Use
Replace 'YOUR_PIXABAY_API_KEY' in the searchImage function with your actual Pixabay API key. You can get this by signing up on the Pixabay website.

Replace '1bY_YTv4NcfV_ir8k-aJXqSlK3_F7EUHWWRtTrYZHSHQ' in the createSlidesFromSheetWithTitle function with the ID of your Google Sheets spreadsheet.

Replace '1LqgBUyUb0LGFyPflW-Fr60K5FjwyX-GTHbv_jY6G588' in the createSlidesFromSheetWithTitle function with the ID of your Google Slides presentation.

Run the createSlidesFromSheetWithTitle function.

Limitations
The Pixabay API has a limit of 5000 requests per hour. If you exceed this limit, you will need to wait until the next hour to make more requests.
The position and size of the text boxes and images in the slides are currently hardcoded. You can adjust these values in the createSlidesFromSheetWithTitle function.
Future Improvements
Add error handling for API requests.
Make the position and size of the text boxes and images customizable.
