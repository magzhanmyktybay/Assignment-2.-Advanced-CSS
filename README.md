# Magzhan Myktybay SE-2540


## Description
A single-page personal website built to practice Flexbox and CSS Grid. The whole page is one Grid layout with a header, a sidebar, a main content area and a footer. Each task of the assignment is a part of this page.


## Task 0
<img width="1919" height="947" alt="image" src="https://github.com/user-attachments/assets/fb366c53-a799-4d61-89d6-05dbfca89fad" />
Navigation bar is constructed using Flexbox. Header has a `display: flex` style with `justify-content: space-between`, that places the logo to the left and the navigation elements to the right and `align-items: center`, that makes them aligned vertically in one line. List of the links is a different flex container and `gap: 28px` ensures the same distance between links. Upon hovering over a link, its color and underline change.  


## Task 1
<img width="1919" height="951" alt="image" src="https://github.com/user-attachments/assets/ad1a5998-2487-4edf-ab39-6f2fda7adb89" />
Three cards have been arranged in a row using Flexbox with gap between them. Each card consists of an image, title, text, and a button. The height of all cards is the same as the items in Flexbox extend their size by default and margin-top: auto takes each button to the bottom of the card. When hovered, the card moves up and becomes shadowed.


## Task 2
<img width="1919" height="949" alt="image" src="https://github.com/user-attachments/assets/159382bc-242c-4961-804b-8c84aea7da9e" />
The entire web page is constructed using CSS Grid. The CSS property grid-template-areas assigns the header (navigation bar from Task 0) to be at the top, the side bar to be on the left side, the main area to the right side, and the footer to the bottom. The grid area is defined by the use of grid-area. The use of grid-template-columns: 240px 1fr assigns the side bar a constant width while the main area uses the remaining space.


## Task 3
<img width="1919" height="980" alt="image" src="https://github.com/user-attachments/assets/0ede91c3-e4d8-45a2-9c0a-b1658c173b12" />
The “Games that inspire me” section contains 9 pictures of the games, displayed using CSS Grid Layout. With the use of grid-template-columns: repeat(3, 1fr), there are 3 columns with an equal width created, and the grid-template-rows: repeat(3, 200px) code line generates 3 rows with an equal height. Thus, all cells have the same dimensions. Gap is used to add equal spacing between the pictures. If the mouse pointer hovers over an image, an overlay containing the title of the game appears. The caption is positioned absolutely and becomes visible when the mouse hovers over the image (opacity: 1).


## Task 4
<img width="1638" height="574" alt="image" src="https://github.com/user-attachments/assets/745bf500-618c-4371-b842-c8577661e3d1" />
Portfolio Page utilizes both Flexbox and Grid Layouts. The header is based on the Flexbox and employs the justify-content: space-between for placing the title on the left side and the GitHub icon on the right side and align-items: center for vertical alignment. The main content area is represented by the CSS Grid with grid-template-columns: 2fr 1fr: the projects occupy the left column while the info occupies the right one. The projects list is arranged in flex-direction: column and the gap. In each project, Flexbox positions the thumbnail next to the text, and flex-shrink: 0 makes the thumbnail non-shrinking. The footer is the final element of the portfolio page.

## Conclusion

In this assignment, I created one website which incorporates Flexbox and CSS Grid together. I realized that Flexbox is effective for one-dimensional layouts where the elements are arranged in either one row or one column such as the navigation bar, card row, the project cards, and the portfolio header. CSS Grid is effective for two-dimensional layouts where both rows and columns are managed simultaneously such as the page layout using grid-template-areas, the image gallery, and the main content of the portfolio.

At the same time, I observed that the two can be used together. The navigation bar acts as a grid item within the page layout while acting as a Flexbox container at the same time, and the gallery caption is aligned through Flexbox within a grid area. Gap property, fr units, and grid-template-areas properties made the layouts more concise to create as compared to margins and fixed widths.
