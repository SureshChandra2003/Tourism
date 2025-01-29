# Tourism

HTML Explanation
Your HTML file defines the structure of a tourism webpage using Bootstrap, CSS, and JavaScript. Here’s what each section does:

Head Section

Links Bootstrap for styling.
Includes jQuery, Popper.js, and Bootstrap JS for interactive elements.
Loads external CSS for styling.
Body Sections

sectionHome: The main homepage with a tourism card and a "Get Started" button.
sectionFavouritePlaces: Displays a list of famous places with images.
sectionTajMahalDetailedView & sectionGoldenTempleDetailedView: Detailed views of tourist spots using a Bootstrap carousel (image slider).
JavaScript Function

The display(sectionId) function (referenced in the onclick attributes) is likely included in the external script (ccbp-ui-kit.js) to show or hide different sections.

CSS Explanation
Your CSS file provides styles to enhance the UI. Key styles include:

Backgrounds

.bg-container: Sets an ocean image as the background for the homepage.
.favourite-places-bg-container: Uses a different background for the favorite places section.
.detailed-view-bg-container: Background for the detailed view pages.
Card Styling

.tourism-card: Styles the tourism introduction card.
.favourite-place-card-container: Designs the favorite places list.
.detailed-view-card-container: Adds styling for detailed descriptions.
Typography

Uses Google Fonts (Roboto, Bree Serif, etc.).
.main-heading, .paragraph, and other text elements are styled for readability.


Output Explanation of Your Tourism Website
Your HTML and CSS code creates a visually appealing tourism website with multiple sections. Here’s what happens when you open the webpage in a browser:

1. Homepage (Ocean Background)
The page starts with a full-screen ocean background.
A white card appears in the center with:
A title (Tourism) styled using the "Roboto" font.
A paragraph with a short description.
A blue button labeled "Get Started", which likely navigates to the next section when clicked.
2. Favourite Places Section
When this section loads:
The background changes to a famous landmark wallpaper (like a tower).
A heading (Favourite Places) appears in white, bold text.
Below the heading, there are multiple cards for different places.
Each card contains:
A small image (80x100 pixels).
A title (e.g., "Taj Mahal", "Golden Temple") in dark blue.
A short description in gray.
3. Detailed View Page
When a user clicks on a place from the "Favourite Places" section:
The background updates to a sea image.
A large heading (Taj Mahal or Golden Temple) appears in white, bold text.
A white card appears below the heading, containing:
A larger image of the place.
A bold blue title.
A detailed description in gray.
4. Styling Features
Smooth Layout: The border-radius and padding create a soft, smooth UI.
Consistent Font: "Roboto" is used for headings and paragraphs.
Button Styling: A rounded, blue "Get Started" button is used for navigation.
Card Alignment: Each section is centered for a clean and structured look.
