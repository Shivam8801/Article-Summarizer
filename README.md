# Article-Summarizer

This is an article summarizer built with the help of RapidAPI and Tailwind CSS. The app can summarize long articles into short paragraphs that convey the main points of the original article.

# Demo
The deployed project can be accessed at https://aigpt8801.netlify.app/

# Installation
To run the app locally, you will need to have Node.js installed. Clone the repository and navigate to the root directory of the project in your terminal. Run the following command to install the required packages:
```
npm install
```
Next, create a .env file in the root directory and add the following variables:
```
VITE_RAPID_API_ARTICLE_KEY=your-rapidapi-key
```
Replace `your-rapidapi-key` with the actual URL and key provided by RapidAPI when you subscribe to the article summarization API.

Finally, start the app by running:
```
npm run dev
```
The app should now be running on http://localhost:3000 or the respective local host.

# Usage
To use the app, simply paste the URL of the article you want to summarize into the input field and click the "Go" button. The app will then fetch the article content, send it to the summarization API, and display the summarized text.

# Credits
This app was built using the following technologies:

`Vite` - A fast and lightweight build tool that leverages ES modules to provide near-instant build times.

`RapidAPI` - A platform that allows developers to discover, use, and manage APIs.

`Tailwind CSS` - A utility-first CSS framework for rapidly building custom user interfaces.

`Node.js` - A JavaScript runtime built on Chrome's V8 JavaScript engine.
