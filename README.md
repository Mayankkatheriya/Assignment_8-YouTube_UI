# Assignment_8-YouTube_UI
## Hosted Link: https://mayankkatheriya.github.io/Assignment_8-YouTube_UI/
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/90e57a59-2697-4da8-ab3e-0bd87c735da7)
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/c1ea7afb-b036-40a8-b14f-782ff616ec65)

HTML part:\
"DOCTYPE html": It indicates the document type as HTML5.\
"html lang='en'": This defines the document's language as English.\
"head": This section holds metadata and resource links for the webpage.\
"meta charset='UTF-8'": It specifies character encoding as UTF-8 for text.\
"meta name='viewport' content='width=device-width, initial-scale=1.0'": This sets the initial scale and responsiveness settings.\
"title": It sets the title of the webpage that appears in the browser.\
"link href='https://fonts.googleapis.com/icon?family=Material+Icons' rel='stylesheet'": This links to Google Fonts for Material Icons.\
"link rel='stylesheet' href='./styles.css'": This links to an external CSS file named "styles.css".

CSS part:

Universal Selector (*):

Sets margins and paddings to 0 for all elements.\
Makes box sizing include padding and border.

Body Selector (body):

Sets font to 'Roboto', with a fallback to sans-serif.\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/a0934a2b-e4ee-4a40-90ce-af575f74db09)
\
\
\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/9219000a-ef99-4b21-916e-a4f1199e0209)
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/de42cacb-d6f0-4b1a-a2f0-503e0d235564)

HTML part:\
"body": This section encompasses the content visible on the webpage.\
"div class='header'": This is the header section of the webpage.\
"div class='header_left'": Within the header, this is the left part.\
"i class='material-icons'": This includes an icon from the Material Icons font.\
"img src='URL' alt='youtube_image'": An image is shown with a description.

CSS part:

.material-icons: Targets elements with class "material-icons," setting their content color to gray.

.header: Styles elements with class "header" as a flex container, aligning items to center vertically, distributing space between items evenly, setting height to 70 pixels, and adding padding of 15 pixels.

.header_left: Styles elements with class "header_left" within "header" as a flex container, aligning items to center vertically.

.header_left img: Styles images within "header_left," setting width to 50 pixels and adding left margin of 10 pixels.

.header_left i: Styles icons within "header_left," adding horizontal padding of 10 pixels and changing cursor to pointer on hover.\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/13ef36f9-e00f-48a3-8894-6bbccb5f1683)
\
\
\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/65d8c15d-59fd-4cb5-9bc5-2334b0a3eb08)
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/f29ce184-c851-4c11-9173-49388588f532)

HTML part:\
Inside the header, there's a "div" element with a class of "header_search". Within this div:

"form action=''": This creates a form for user input.\
"input type='text' placeholder='Search'": An input field is present for users to type in, with the word "Search" as a placeholder.\
"button": A button element is included.\
"i class='material-icons'": This adds an icon from the Material Icons font.\
"button closing tag": This ends the button element.\
"form closing tag": This concludes the form.

CSS part:

.header_search form:

Selects the form element within elements with the class "header_search."\
Adds a 1px solid border with color #ddd.\
Sets a height of 35px.\
Clears margin and padding.\
Utilizes flexbox for arranging child elements.

.header_search input:

Selects the input element within elements with the class "header_search."\
Defines a width of 500px.\
Adds 10px of padding on all sides.\
Clears margin.\
Sets the height to 100% of its containing element.\
Removes borders and border radius.

.header_search button:

Selects the button element within elements with the class "header_search."\
Clears padding and margin.\
Sets the height to 100% of its containing element.\
Removes borders and border radius.\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/f7bccf16-798f-498e-8ac8-8cc479a5fb98)
\
\
\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/d03b7e0a-9679-4eaf-a787-031cf09745cf)

HTML part:\
Inside the "header" class, another "div" element with a class of "header_search" is added. Within this div:

"form action=''": This forms a structure for user input.\
"input type='text' placeholder='Search'": An input field is displayed for users to input text, and "Search" is shown as a placeholder.\
"button": A button is included.\
"i class='material-icons'": An icon from the Material Icons font is inserted.\
"button closing tag": This closes the button element.\
"form closing tag": This concludes the form.

CSS part:

No CSS required for this step because we already define material icons property above\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/2e2d6705-08ac-49bf-87c0-f191e6dfd0c1)
\
\
\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/29bb261d-f21e-4877-ac1f-92cb6e734d53)
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/16d9fe94-8ab8-4e5e-84b2-9a9845638ef1)

HTML part:\
Inside the "main" class, a "div" element is present. Within this div:

"div class='sidebar'": This represents a sidebar section.\
"div class='sidebar_categories'": Inside the sidebar, a div holds categories.\
"div class='sidebar_category'": Within the categories, a div represents a single category.\
"i class='material-icons'": This includes an icon from the Material Icons font.\
"span": A span element holds text content.

CSS part:

.main:

Utilizes flexbox for layout.\
Conceals content overflow.\
Sets the height to the viewport height minus 70px.

.sidebar:

Takes up the full height of its container.\
Has a width of 230px.\
Displays a white background.\
Enables vertical scrolling overflow.

.sidebar_categories:

Occupies the entire width.\
Uses flexbox for vertical alignment and stacking.\
Adds space at the bottom and top margins.

.sidebar_category:

Uses flexbox to align items horizontally.\
Applies padding to the top and bottom (15px) and the sides (25px).

.sidebar_category span:

Provides space to the left (15px) of the text.

.sidebar_category:hover:

Changes the background color to a light gray when hovered.\
Changes the cursor style to a pointer.

.sidebar::-webkit-scrollbar:

Styles the scrollbar.\
Hides the scrollbar (display:none) using the WebKit CSS pseudo-elemen\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/8279eb99-38a5-4a9e-be75-976d9fd4384b)
\
\
\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/886722d7-cd4a-41cd-b9e6-c700c7eca4b8)

HTML part:\
Inside the "sidebar," you've created another "div" element. Here's the continuation of the explanation:

Within the "sidebar" div:

"div class='sidebar_categories'": Inside the sidebar, another div holds categories.\
"div class='sidebar_category'": Within the categories, a div represents a single category.\
"i class='material-icons'": This adds an icon from the Material Icons font.\
"span": A span element holds text content.

CSS part:

No CSs required fir tyhat part of code,  because everything defined above already\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/532ebde3-8bd8-4632-a9f4-42127b56e90c)
## our side bar is ready,  now its time to make our video section inside main section
\
\
\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/56f20ff8-8e63-4651-9313-f82f876cd9d7)
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/19ec6484-eff2-47f1-8e5d-0dbb317f41a0)

HTML part:\
Inside the "videos" div:

"h1": This sets a heading for the section, indicating "Recommended."\
"div class='videos_conatiner'": This div contains video content.\
"div class='video'": Each div represents a single video.\
"div class='video_thumbnail'": Inside the video div, this div contains the video's thumbnail.\
"img src='URL' alt=''": An image is shown with a URL and an empty alt attribute.

CSS part:


![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/ce5404d1-d28c-4d1a-bfa8-473816a7dea9)
\
\
\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/1e2d4235-c372-4662-b1e6-c237c57a9a5d)
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/504f3e80-f8b0-4d21-9cb7-91f53c9c7575)

HTML part:\


CSS part:

![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/c657b782-6b81-4e9c-a54e-7083505c844a)
\
\
\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/da80d3fe-dc1c-4a63-86ea-d4a1ac5202aa)
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/e654ac6b-d36f-493d-944d-d94039166257)

HTML part:\


CSS part:

![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/8d35a77c-c06d-498e-9df0-4193c2b90c6d)
\
\
\
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/e2d8950c-6b80-4651-afc0-42387aec0897)
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/3bdf80ee-9fa7-4b52-845a-20c802ca7a32)

HTML part:\


CSS part:

![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/6f851718-28a0-42e9-839f-030f0262a88c)
\
\
\
copy and paste the div of class "video" as many time as you want
## And your Webpage is ready......
![image](https://github.com/Mayankkatheriya/Assignment_8-YouTube_UI/assets/128832286/d08df934-d0f8-4d36-ba45-b88bb7327c22)
# Thankyou




