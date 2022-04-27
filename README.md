# ✨ Graphic Design Process Documentation

## 3/31

For 3/31, I sketched the basic shape of the entire admin panel, including the following detailed parts as listed follow,

- Navbar
- Signin, Signup page
- Profile page
- Preference page
- Chat page
- Event, calendar page
  - Year
  - Week
  - Days
- Invoice page
- Analytics page
- Main dashboard page

These above are the main features should be noted in an admin panel for better user experiences yet a complex and featured panel for more usages. An admin panel should have two color schemes, dark and light as according to design principle by MDUI (Google material design principle), also a dark-light system fits the SEO standards for web search & responsive designs. I mainly created the light version of the admin panel, including the navigation bar and it's affiliated dropdown menu. Besides this, a good font should also be presented on the panel, the font family I chose was *jet Brains Mono* & *Open Sans*, these two fonts are all available on Google Fonts, note that the former fonts was released under MIT license, and the latter was released under OTF license, so it is fully available and free for non-commercial uses.

## 4/11

For 4/11, I have achieved my general purposes and required basis of my design, I started digging into the detailed part of the navigation bar, I made my navigation bar into divided follow as shown in the image below.

![](images/nav.excalidraw.png)

The image include a basic structure of a navigation bar in general, starting from left to right, the rectangle indicates some text and, the vertical rectangle below indicates a dropdown menu with some text inside with some text,
navigate to the right, a easy search bar present as follow, when the user click on to the search bar, it presents the follow interaction as indicated in the image.

![](images/search.excalidraw.png)

<small>Besides this hand-drawn styled images are created on Excalidraw</small>

The image here indicates when a user click on the search bar, the search bar will pop into an isolated `pjax` powered bigger search tab in the window, when user search the word inside, related result will be shown in the following box, the matching keywords will be marked/highlighted for easier recognition. The placeholder text font there is JetBrains mono font. The circle button on the very right is the dark-light switching button, the interaction is achieved as in follow gif.

![](images/dark-light.gif)

The dark mode and light mode style design was took from my own blog page, it was originally created in figma, and rewrote into a functional dark-light system via `CSS` & `JS`!

Besides the search bar, the sign up page is also mostly done, the rough sketch is shown in the following image,

![](images/signup.excalidraw.png)

The signup page is just simply achieved via two seperate tab, the sketch there shows a rectangular shape, but in my design, all parts has a rounded corner.

## 4/13

For 4/13, I fixed some lining issue and padding issue with signup page to make it more responsive, and I added a small dark-light button to the bottom of the sign in page. Besides this I also started creating the profile page, this relatively took longer then I expected, the profile page is still in progress with avatar portion, bio, and other additional information, besides this I also finalized login/signup page design as shown follow,

| Login | Signin |
| ----- | ------ |
| ![](images/login.png)     |  ![](images/signup.png)      |

This page is in dark mode, but I didn't decide to work on light mode right away because it might break the entire color scheme of the panel, so after I finish dark mode, I'll change and adjust the color scheme to light mode universally. (Don't ask me why I did nav bar with light mode first, I thought it was easier, but no it was not).

## 4/15

For 4/15, I continued working on my profile page, but I met a lot of padding issues, and the worst thing happened, my figma crashed, since figma is a web app, it took at least half an hour for me to actually close the web page from my browser, so I decided to move on to the next part, the preference page and go back to the profile page, the preference page seemed not be a page, but more of like a multifunctional side bar with options listed inside, the design is shown follow. After I finished the sidebar, I worked on the profile page based on the inspiration of monsnary layout.

| sketch                             | Finalized               |
| ---------------------------------- | ----------------------- |
| ![](images/profile.excalidraw.png) | ![](images/profile.png) |



The inspiration was came from http://graphicburger.com/flat-design-ui-components/. The link attached above.

## 4/19

For 4/19, I continued working with the profile page with some personal stats and graphs, the idea was inspired by Apache ECharts, it's an open source project written in Typescript that serves beautiful web charts for direct localization, it is shown follow, besides this I didn't work on other things due to PCR testing.

| Stats Graph        | Basic Graph           |
| ------------------ | --------------------- |
| ![](images/os.png) | ![](images/graph.png) |

This two tiles is located under profile.

## 4/21

Today I gradually finished my profile page, but the worst thing happened, my app crashed, entirely, my figma account was suspiciously marked as "flagged" out of no reason, I contacted the figma community, they said I have to wait for 1-3 days in order for a full response, so I was not able to get into figma for further designs but I migrated my work into AI.

I ultimately digged into my dashboard page, I started working on the dashboard with a further sketch that divide the parts into the following, a good dashboard should follow the principle as described in MDUI elements,

- Consider your audience.
- Determine your goals.
- Choose relevant KPIs.
- Tell a story with your data.
- Provide context.
- Don't try to place all the information on the same page.
- Select the right type of dashboard.
- Use the right type of chart.

| Sketch                          | Dashboard V1         |
| ------------------------------- | -------------------- |
| ![](images/dashboard.excalidraw.png) | ![](images/dashboard1.png) |

A dashboard should clearly tell the user what is going on, what is going next, and set the important details alarmed to get attention from the user, so this is what I tried to do. The top part is the welcome message, which will be likely user-friendly and it also forms as a feature of placeholder to make the page not so empty, and the following is the main three important part to let my user get attention: email, projects, and user. Users can easily find out what is happening with them and what they have to do. The next following are two graph, bar charts and line graph, these two graph could be used in any scenario to describe statistics happening at presents, and the inspiration of the charts still comes from Apache ECharts.

## 4/25

**Happy 17th birthday to me!!! :)**, for todays work, I mainly focused on fixing small details and padding issues with the dash board itself and make it responsive on mobile look, as follow,

| Static View            | Dynamic View         |
| ---------------------- | -------------------- |
| ![](images/mdash1.png) | ![](images/mdash.gif) |

And thanks to Google Chrome's built in mobile view and desktop view switching feature for me to achieve this goal, and the mobile model used is IPhone X, the standard mobile view model.

## 4/27

For 4/27, I mainly focused on the dashboard's second part, the version 1 of the sidebar, the sidebar contains the following, a search bar, and quick navigation buttons, also dropdown menu for wider usages,

| Sketch                 | Sidebar V1                  |
| ---------------------- | --------------------------- |
| ![](images/dashsidebar.excalidraw.png) | ![](images/dashsidebar.png) |

I didn't finish the dropdown menu part, since I was called out for PCR.