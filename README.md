# Google Review Link Generator

The **Google Review Link Generator** is a simple web application that allows users to generate a direct link for Google Reviews for any place. By entering a location, users can easily obtain the permanent  review link and copy it to their clipboard.
unlike most other free services this link doesnot expire fast or redirect you to any advertisement pages before redirecting to the review page

## Features
- **Autocomplete Search**: Search for places using Google Places Autocomplete.
- **Review Link Generation**: Generate a direct link for Google Reviews.
- **Clipboard Copy**: Copy the generated review link to the clipboard with a single click.

## Prerequisites

- Basic knowledge of HTML and JavaScript.
- A valid Google Maps API key , the one provided in this code might expire , still check your luck .

## Instructions

### Step 1: Prepare the HTML File

Download the provided HTML file:

### Step 2: Modify the API Key

- Open the downloaded file in any text editor.
- Locate the following line:

  ```html
  <script src="https://maps.googleapis.com/maps/api/js?key=A000IzaSyB41D000RUbKWJH000PxaFjM000AwdrzWzbVKartNGg&callback=initMap&libraries=places&v=weekly" defer></script>
  ```

- Remove the nine zeroes from the API key. i have added nine zeroes inside in the format  000 000 000 for security reasons , remove it before using :

  <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_ACTUAL_API_KEY&callback=initMap&libraries=places&v=weekly" defer></script

  You can also Replace `YOUR_ACTUAL_API_KEY` with your actual Google Maps API key.

### Step 3: Save and Open the File

- Save the changes in your text editor.
- Open the saved HTML file in a browser by right-clicking the file and selecting "Open with browser" .

## Usage

1. **Search for a Location**: Enter a location in the input box.
2. **Select the Place**: Choose the desired place from the autocomplete suggestions.
3. **View Details**: The map will center on the selected place, displaying its name, address, and total reviews.
4. **Copy Review Link**: Click the "Copy Review Link" button to copy the Google Review link to your clipboard.

## Conclusion

This Google Review Link Generator makes it easy to create and share review links for any place. Ensure your API key is correctly set up and enjoy the convenience of generating Google Review links effortlessly. , hosting this will not prorbably work , try you luck and inform me if it worked
