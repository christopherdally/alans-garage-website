# Alan's MOT Garage 

The purpose of this project is to design a fully responsive website for a local car garage that currently doesn’t have an online presence at the moment. the goal of the website is to provide information to the end user about the local garage. 

![Responsice Mockup](/wireframe/3-devices-black-mockup.png)

## Features 

The features of the website are the following;
1.	Contact page with form
2.	Reviews from Google
3.	Contact Details
4.	Social Links
5.	Main navigation 
6. Color scheme for website as follows
	1. #0A2647 				#144272 			#205295 			#2C74B3
		rgb(10, 38, 71)		rgb(20, 66, 114)	rgb(32, 82, 149)	rgb(44, 116, 179)	

![Wireframe of Garage Website](/wireframe/wireframe.png)

## Testing 

All features on the site were tested to ensure the responsiveness of the site across all devices. Contact form transfer to thank you page to tell customers of the message sent. Reviews on the home page tell users of how the garage performs with customers.

Site was deployed to git pages for more testing found that the overflow of page so ammended the div spacing to sort this out.


## Issues/Changes 

### 7th March 2023 - 

1. Bootstrap Menu not loading figured out that I didn't paste Javascript onto the page hence why it wasn't working
2. Most of the site is now designed just need to configure smaller screen sizes 

### 8th March 2023 -

1. Add the phone number and address to the top of the page below the navigation
2. Design the site to be responsive as services and contact details weren't right
3. Decided to go with separate services pages for the following (Vehicle Servicing, Tyres, MOT's and Vehicle Repairs) as I believe this would be better for the SEO scores.
4. Add meta keywords and descriptions to all pages again this is for a better SEO.
5. Deployed website via git on my server run by Plesk for testing purposes at https://musing-archimedes.109-228-60-76.plesk.page/.
	1. Also deployed to GitHub pages link https://christopherdally.github.io/alans-garage-website/
6. Run CSS Validator - All clear apart from font awesome
7. Run HTML Validator
	1. Change the header image section to a div instead of a section
	2. Removed height and width of the iframe (reviews)
8. Added id to iframe reviews to ensure the website passes HTML Validator
9. Added Vehicle Servicing Page
10. Added Contact Us page
11. Embedded Google Maps to Website Contact Page
12. Changed styling on the contact page button as the mobile version wasn't showing the full button name
13. Created the remainder of the site pages
14. Minor changes
	1. Vosa icon on the bottom of every page
	2. Active page in Nav bar update

### 10th March 2023 -

1. Changed the default bootstrap navbar background color and link to better suit the site.

### 11th March 2023 -

1. Changed the colour for toggle menu
2. Contact form changed to required input fields

### 13th March 2023 -

1. Change header image size due to not expanding enough on larger screen sizes
2. Changed the Readme styling using markdown
3. Updated readme file and added mockup

### 14th March 2023 -

1. Changes to styling to stop overlay on page for header and reviews div
2. Added pictures to services pages
3. Format documents
4. Change styling to contact page on mobiles
5. Added contact form thank you page

### 20th March 2023 -

1. Final changes add comments to review section and contact pages
2. Checked to make sure the site is fully operational

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fchristopherdally.github.io%2Falans-garage-website%2F)
- CSS
  - Only errors found on CSS Validator was the css being used on the bootstrap css file not ones that are designed for this project [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fchristopherdally.github.io%2Falans-garage-website%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs

None that I am aware off

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://christopherdally.github.io/alans-garage-website/ 


## Credits 

1. Font awesome v4 used for the site icons
2. All media images used for site purchased through adobe stock free
3. Bootstrap V5 used for navigation menu
4. Used Colorhunt.co website to generate a colour scheme for the website https://colorhunt.co/palette/0a26471442722052952c74b3
5. Google maps imbedded on to contact page
6. Used Sociable Kit (https://www.sociablekit.com/) to embed Google reviews on the site

## Other General Project Advice

1. Realised that some of my intial commit message wasn't to form but since then made sure that they was right