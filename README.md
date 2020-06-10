## We Love Trance!

In my spare time I produce trance music. So I came up with the idea to showcase my music by building a website which lets people listen to it, and provide links to purchase the music. There is also a page for people to sign up for new release dates and a newsletter.

I decided on a home page that would act as a biography, a listen page so people can stream my music, and a sign up page for people to leave their email address for updates on new releases. I can go back to completing this when I have learnt the appropriate back end programming.

## UX

The aim for my website was to showcase my music. I felt that the layout should be simple and took inspiration from the bootstrap tutorials and worked in thirds. I wanted to have the same navigation and footer across all three pages for both simplicity and ease of use for visitors to the website.

For the user visiting my website, they will want:

  * To know more about me as a producer,
  * Listen to some of my music,
  * Potentially buy the music and/or sign up for updates.
  * Want a mobile friendly website to visit whilst on the go via a mobile phone/tablet
  
My website has been split into pages specifically for each of these user goals. 

  * The biography on the index.htm page has a little about me as a producer, where I from and my background,
  * The listen.html page has four tracks that I've produced for the user to stream from soundcloud via my website,
  * A sign up page for the user to enter their email address to recieve updates on future release dates, gigs, and a newsletter.



I created a wireframe of which the file is in the wireframe directory. This was the first time using wireframes so it was quite simple in design but it put across how I wanted my website to look. Minor deviations from the wireframe structure were made whilst writing the code but on the whole, the layout is the same.

Due to the use of Bootstrap technology, the whole website collapses into a nicely presented format when viewed on mobile. 

At the time of me doing the project, I have started the process of monetizing my tracks, so that the link from the buy menu will actually take the user to spotify or soundcloud to purchase the music.

## Technologies Used

My project uses HTML and CSS in conjunction with the Bootstrap Framework. I used Google Fonts for the texts and font awesome for the icons.

 * https://fontawesome.com/start

 * https://fonts.google.com/

 * https://www.bootstrapcdn.com/
 
I have used these because during my studies so far, I have learnt how to use these to incorporate into websites. I felt the icons were a good fit for what I was trying to achieve. The fonts I've used I felt also fit into the type of website it is.

I took pictures from pixabay to use in my project. I used these as they are royalty free and cost nothing. The pictures used are of the highest quality and represented the page of where it was used in my project.

 * https://pixabay.com/

I have used the same logo that I created for all of the pages. Because of this, I used a color picker website to determine the color scheme of the website.

 * https://html-color-codes.info/colors-from-image/
 
From these colors, I used a website that helps determine primary and secondary color themes:

 * https://material.io/

## Features

### Existing Features

 * Logo - I have created my own logo which takes the space at the top left of all three pages and provides a link back to my home page. I have taken the color scheme from this.
 * Navbar - The navigation bar, like the logo, is the same across all three pages. There are four links, home, listen, buy, signup. Each link has it's own icon which pulses once hovered over. Home, listen and signup take the user to each of the three pages within my website whilst buy takes the user to an external website in a new browser page.
 * Footer - The footer has four links, made up of icons. Facebook, Soundcloud, YouTube and buy. To the right of these, a copyright. I decided on reversing the bootstrap configuration I used for the header as I thought it looks aesthetically pleasing, and was easy to implement, creating less work thus saving on time. Each link opens in a new browser page.
 * Sections - Each section provides the user with what each page intends. There is a picture on the left of each page, all linking to the home page. Home is a biography and an email for the user to contact myself. The listen page enables the user to listen to four of my tracks. The sign up page enables the user to sign up for information on new releases, gigs and a newsletter. The code for the embedded tracks were copied from my soundcloud page and tweaked.
 
### Features to Implement

The buy link will in future take the user to a website to purchase my music. I am currently setting this up with Soundcloud, Spotify and Apple Music. The links can be edited when this is complete. The facebook and YouTube links take the user to the home pages of these website until I have set up each external page accordingly.

## Testing INCOMPLETE/NEEDS EDITING

I have published my project for peer review on Slack.

During my own testing process, I have clicked on each link on each page to check it worked as expected. The logo and all the pictures take the user to the home page, as does the home button. All of the footer icons take the user to the relevent web pages on a new tab.

On the home page, the link to my email works as intended. It opened my email application on my laptop.

The tracks on the listen page all play as intended when clicked on the play button.

The form on the sign up page prompts when the user does not put information in correctly.

I have used developer tools on google chrome throughout the project to make sure everything looks as intended on both mobile devices and larger screens. I also used this process to check all of the above on various media sizes.

I did encounter a slight problem midway through my project. I'm not exactly sure what I done but after replicating the footer and header on all three pages, there seemed to be a margin above three of the navigation bar items as I resized the screen to smaller areas. I only noticed after committing the code. I hadn't added any other HTML or CSS so I couldn't understand why this had happened so I had to go back to the previous commit and use the code from there. I also pulled the .list-inline-item:not(:last-child) from the tutorial in the mini project to stop content from wrapping underneath. This solved the problem. 

## Deployment INCOMPLETE/NEEDS EDITING

Before submission, I have deployed my code onto Git Pages. I done this by going into settings under my repository and under "GitHub Pages", used the Source drop-down menu and selected a publishing source of master branch.

 * Live Website: https://markdennisuk.github.io/We-Love-Trance/
 * GitHub Repository: https://github.com/MarkDennisUK/We-Love-Trance

This was done before mentor review and may need some changes.

### Media

 * www.pixabay.com (photos)

### Acknowledgements

 * Mini Project Tutorials
 * https://html-color-codes.info/colors-from-image/
 * https://material.io/resources/color/#!/?view.left=0&view.right=0&primary.color=212121&secondary.color=FF1744
 * https://fonts.google.com/
 * https://fontawesome.com/start
 * https://www.w3.org/WAI/GL/wiki/Using_aria-label_to_provide_labels_for_objects
 * https://www.bootstrapcdn.com/
 * http://shoelace.io/
 * https://soundcloud.com/mark-dennis-uk/
 * https://cdnjs.com/
