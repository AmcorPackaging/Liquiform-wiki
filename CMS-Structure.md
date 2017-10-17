## Space:
Contentful organizes content into spaces, that allows you to group all the related resources for a project together, this includes content entries, media assets, and settings for localizing content into different languages.

Our space name is: `LiquiForm` inside `Amcor` organization.

Each space has a content model that represents the content types you create.
____

## Content Types:
A content type consists of a set of fields and other information.

Structure of LiquiForm Content Types:

### Home
![Home](./images/artboardHome.png)
### How it Works
![How It Works](./images/artboardHowItWorks.png)
### FAQ
![FAQ](./images/artboardFaq.png)
### News
![News](./images/artboardNews.png)
### News Item
![News Item](./images/artboardNewsItem.png)
### About Us
![About US](./images/artboardAboutUs.png)
### Contact
![Contact](./images/artboardContact.png)
_____

### Schema

- _logo_:
  - image: Image for the logo of LiquiForm.

- _headerContent_:
  - page: Required field, indicates what page is refering this data.
  - headerTitle: Text for the header title.
  - headerContent: Text for the header content.
  - headerImage: Image for the header image.

- _homeContent_:
  - primaryContent: Text for the 1st part of the content.
  - secondaryContent: Text for the 2nd part of the content.
  - imageContent: 1st Image.
  - imageContent2: 2nd Image.

- _youtubeVideo_:
  - title: Text for the title of the video. (Not displayed)
  - summary: Text for the summary of the video.
  - videoId: Text with the YouTube Id, usually in the url. (not displayed)
  - url: Text for the URL of the YouTube video. (not displayed)
  - order: Number to order the videos. (not displayed)

- _benefit_:
  - title: Text for the benefit title.
  - content: Text for the benefit content.
  - icon: Text for the benefit icon. Refers to the [Font Awesome icon library](https://fontawesome.io/icons)
  - order: Number to order the benefits.

- _faq_:
  - title: Text for the title of the FAQ.
  - content: Text for the content of the FAQ.
- _news_:
  - title: Text for the title of the News.
  - summary: Text for the summary of the News.
  - tag: Text for the tags of the News (not displayed).
  - date: Date of the News.
  - content: Text for the content of the News.
  - image: Image for the News.
  - imageAlt: Text Alternative of the Image for search engines.

- _aboutContent_:
  - primaryContent: Text for the About Us section.
