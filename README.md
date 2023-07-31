<a name="eli5"></a>

# eli5-chrome

#### <ins>__*a google chrome extension for eli5*__</ins>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#view">Project Overview</a>
      <ul>
        <li><a href="#obj">Objectives</a></li>
      </ul>
    </li>
    <li><a href="#uiux">UI/UX</a></li>
    <li>
      <a href="#tech">Technologies and Programming Languages</a>
      <ul>
        <li><a href="#front">Front-end (User Interface)</a></li>
        <li><a href="#back">Back-end</a></li>
        <li><a href="#ml">Machine Learning (ML) Libraries</a></li>
        <li><a href="#ide">IDEs (Integrated Development Environments)</a></li>
        <li><a href="#ml">Development Environment</a></li>
      </ul>
    </li>
    <li>
      <a href="#map">Roadmap</a>
      <ul>
        <li><a href="#line">Timeline</a></li>
        <ul>
          <li><a href="#time">Time Estimate</a></li>
        </ul>
        <li><a href="#todo">To-Do List</a></li>
      </ul>
    </li>
    <li><a href="#start">Getting Started</a></li>
    <li><a href="#flow">Basic Workflow</a></li>
    <li>
      <a href="#io">Basic I/O Details</a>
      <ul>
        <li><a href="#i">Input</a></li>
        <li><a href="#o">Output</a></li>
        <li><a href="#sys">System Requirements</a></li>
        <li><a href="#user">User Requirements</a></li>
      </ul>
    </li>
    <li>
      <a href="#use">Usage</a>
      <ul>
        <li><a href="#pre">Prerequisites</a></li>
        <li><a href="#inst">Installation</a></li>
      </ul>
    </li>
    <li><a href="#feat">Key Features</a></li>
    <li><a href="#give">How to Contribute</a></li>
    <li><a href="#plus">Future Enhancements</a></li>
    <li><a href="#lic">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#ack">Acknowledgments</a></li>
  </ol>
</details>
  

---------------------------

<a name="view"></a>
## Project Overview

Have you ever found yourself stumbling upon perplexing terminologies while browsing articles, forums, or research papers? `eli5-chrome` is here to bridge the comprehension gap, making knowledge more accessible to users of all ages and backgrounds.

Whether you are a curious student, an avid learner, or someone who simply wants to delve into unfamiliar subject matter, `eli5-chrome` empowers you to effortlessly comprehend the most intricate topics the internet has to offer.


`eli5-chrome` is implemented as a Google Chrome extension that provides users with ELI5 (*"Explain Like I'm 5"*) definitions and descriptions of words or phrases on the web.


Drawing inspiration from the immensely popular subreddit *r/ELI5*, this extension equips users with a newfound understanding of intricate jargon by effortlessly displaying simplified explanations upon hovering over challenging words or phrases.
> The extension sources its knowledge directly from the r/ELI5 subreddit, renowned for its community-driven ELI5 explanations that break down complicated subjects into easily digestible nuggets of knowledge.


#### <ins>*For terms not yet queried on r/ELI5...*</ins>
The extension leverages state-of-the-art Machine Learning (ML) techniques &mdash; auto-generating pseudo-"r/ELI5" explanations.
  - Through data scraping and intelligent algorithms, `eli5-chrome` composes ELI5-style definitions, mimicking the subreddit's signature simplicity even for previously unexplored concepts.
    
#### <ins>*If a term/phrase has, in fact, already been queried on r/ELI5...*</ins>
Users can view relevant snippets derived from top-rated comments curated through Reddit's various sorting mechanisms.
  - __<ins>Note</ins>:__ By default, `eli5-chrome` will provide both its ML-generated definition as well information it aggregates from r/ELI5. By default, `eli5-chrome` will also utilize Reddit's "top" sorting mechanism for comments.
    - This ensures users receive insights from diverse perspectives and in-depth understanding of the term's context.
These configurations can be changed in `eli5-chrome`'s user settings.



<a name="obj"></a>
### <ins>Objectives</ins>
The main objective of `eli5-chrome` is to provide macOS users with a playful solution to amplify their audio volume beyond the limitations imposed by Apple. 

By offering a user-friendly interface and a humorous touch, `eli5-chrome`` aims to enhance the audio experience for users who desire louder sound without compromising on quality.

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------

<a name="uiux"></a>
## UI/UX
`eli5-chrome` offers an intuitive and user-friendly interface, seamlessly blending into the browsing experience.\
The extension's efficient storage management ensures quick access to previously queried terms, enhancing response times for recurrent usage.

When hovering over a word/phrase, the extension provides a little drop-down widget containing the ELI5 definition.\
The widget promptly vanishes when the mouse moves away, ensuring an unobtrusive browsing experience.


Moreover, user privacy and data protection are at the forefront, as the extension does not collect or store any personal information, ensuring a secure and trustworthy environment.

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------

<a name="tech"></a> 
## Technologies and Programming Languages

<a name="front"></a> 
### Front-end (User Interface):
>
> - **<ins>HTML/CSS</ins>:** Used for creating the user interface of the extension.
>   - HTML structures the elements, while CSS styles them to ensure an appealing and consistent look.
> - **<ins>JavaScript (ES6+)</ins>:** The core language for developing Chrome extensions.
>   - It allows you to manipulate the Document Object Model (DOM) and interact with web pages.


<a name="back"></a> 
### Back-end: 

> - **<ins>Node.js</ins>:** A popular server-side runtime environment that allows for JavaScript execution outside the browser, making it ideal for handling background tasks and API calls.
> - **<ins>Express.js</ins>:** A lightweight Node.js framework for building the back-end server, handling routes, and managing API requests.
> - **<ins>Axios</ins>:** A JavaScript library for making HTTP requests, which will be used to interact with the Reddit API and perform data scraping.


<a name="ml"></a> 
### Machine Learning (ML) Libraries:

> - **<ins>TensorFlow.js</ins>:** An open-source JavaScript library for training and deploying ML models in the browser. It enables seamless integration of ML techniques for generating pseudo-r/ELI5 explanations.

<a name="ide"></a> 
### IDEs (Integrated Development Environments):

> - **<ins>Visual Studio Code (VS Code)</ins>:** A versatile code editor with extensive support for JavaScript, Node.js, HTML, and CSS, along with numerous extensions for additional functionalities.
> - **<ins>WebStorm</ins>:** An intelligent IDE that provides excellent JavaScript and Node.js development capabilities, as well as advanced HTML and CSS support.

&nbsp;


<a name="built"></a>
### Built With:

> Put
> Shit
> Here

<a name="devenv"></a>
### Development Environment:

> - **Operating System:** macOS Ventura *(version 14.3.1)*
> - **Architecture:** Apple arm64


<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------

<a name="impl"></a>
## Implementation Details

1. **Manifest File:** Create a `manifest.json` file to define the extension's properties, including permissions, content scripts, background scripts, icons, and the extension popup.
2. **User Interface (UI):**
- Design the popup widget using HTML and CSS. It should be visually appealing and responsive to different screen sizes.
- Implement JavaScript logic to handle user interactions and events, such as hovering over words/phrases.
3. **Content Script:**
- Develop a content script to inject JavaScript code into web pages and detect the highlighted words/phrases.
- Handle communication between the content script and the background script.
4. **Background Script:**
- Create a background script to handle requests to the Reddit API, data scraping, and ML-based pseudo-r/ELI5 generation.
- Implement communication between the background script and the content script.
5. **Reddit API Integration:**
- Register your extension with the Reddit API to obtain the necessary authentication credentials.
- Use the credentials to fetch data from the r/ELI5 subreddit, including relevant comments for queried terms.
6. **Machine Learning (ML) Techniques:**
- Set up ML libraries and models for natural language processing (NLP).
- Train the models on relevant data to generate pseudo-r/ELI5 explanations for terms not on r/ELI5.
7. **Data Scraping:**
- Implement web scraping techniques to gather information from other online sources to supplement pseudo-r/ELI5 explanations.
8. **Storage Management:**
- Utilize Chrome's storage API to store user preferences and cache frequently accessed terms.
- Develop mechanisms to manage and update the storage efficiently.
9. **Error Handling:**
- Implement robust error handling to gracefully manage any connection issues, API failures, or ML errors.
- Display appropriate error messages to the user when necessary.
10. **Testing and Debugging:**
- Perform extensive testing of the extension on different websites and scenarios to ensure stability and compatibility.
-Debug and resolve any issues that arise during testing.
11. **Packaging and Deployment:**
-Package the extension into a distributable format (*e.g.*, `.crx`) for Chrome Web Store submission.
- Optionally, deploy the extension to the Chrome Web Store to make it publicly available for users.

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------

<a name="map"></a>
## Roadmap

> Put
> Shit
> Here

<a name="line"></a>
### Timeline: 

> ##### <ins>__Started__</ins>: Not yet
>
> ##### <ins>__Completed On__</ins>: Idk
>
<a name="time"></a>
>
### Time Estimate: 
> 
> This project's estimated timeline is 3 months, with the following breakdown:
>
> Initial Setup and UI Development: 1 week
> Reddit API Integration and Data Retrieval: 2 weeks
> Machine Learning Model Development: 3 weeks
> Data Scraping and Pseudo-r/ELI5 Generation: 2 weeks
> Storage Management and Error Handling: 1 week
> Testing, Optimization, and Polishing: 2 weeks

&nbsp;
  
<a name="todo"></a>
### To-Do List: 
- [ ] Create a New macOS SwiftUI Project
- [ ] Pseudocode
- [ ] Add Additional Templates w/ Examples

> Put
> Shit
> Here

&nbsp;


- [ ] **Reddit API Integration:** Implement a connection to the Reddit API to fetch data from r/ELI5, including comments, for queried terms.
- [ ] **Machine Learning (ML) Techniques:** Employ natural language processing (NLP) and ML algorithms to generate pseudo-r/ELI5 explanations for terms not found on r/ELI5.
- [ ] **User Interface:** Create a user-friendly interface that displays the ELI5 definition in a drop-down widget when the user hovers over a word/phrase.
- [ ] **Storage Management:** Utilize Chrome's storage API to manage user preferences and cache frequently accessed terms for improved performance.
- [ ] **Data Scraping:** For terms not found on r/ELI5, scrape relevant information from other online sources to create informative pseudo-r/ELI5 explanations.
- [ ] **Error Handling:** Implement robust error handling to gracefully manage any connection issues, API failures, or ML errors.


<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------
<a name="start"></a>

## Getting Started

1. Clone the repository and navigate to the project directory.
2. Install any required dependencies using `npm` or `yarn`.
3. Load the unpacked extension in Chrome Developer mode.Code or VSCode when necessary.

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------
<a name="flow"></a>
## Basic Workflow Guide

1. Set up the basic project structure and necessary files.
2. Create a basic UI for the extension's pop-up widget.
3. Implement Reddit API integration to fetch data from r/ELI5.
4. Develop ML models to generate pseudo-r/ELI5 explanations for terms not on r/ELI5.
5. Integrate data scraping to supplement pseudo-r/ELI5 explanations.
6. Add storage management to store user preferences and cache frequently accessed terms.
7. Implement error handling to deal with API or ML failures gracefully.
8. Test the extension for different use cases and scenarios.
9. Optimize and fine-tune ML models for better explanations.
10. Polish the UI and user experience for seamless interaction.
11. Perform extensive testing and debugging to ensure stability and reliability.

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------

<a name="io"></a>
## Basic I/O Details

<a name="i"></a>
### Input:
> - Users provide input by hovering the cursor over a word/phrase on any webpage.
>   - When the user hovers the cursor over a word or phrase on any webpage, the extension detects the highlighted term and initiates a request for the ELI5 explanation.
>
<a name="o"></a>
### Output:
> - ELI5 definition appears in a drop-down widget, along with relevant r/ELI5 comments or auto-generated pseudo-r/ELI5 explanations.
>   - The ELI5 definition appears in a non-intrusive drop-down widget adjacent to the highlighted word/phrase.
>   - The widget disappears as soon as the mouse moves away from the term.
>   - If the word/phrase has been queried on r/ELI5, the widget will display relevant comments sorted by Reddit's "top" mechanism.
>   - If the term/phrase has not been queried yet on r/ELI5, the widget will show an auto-generated pseudo-r/ELI5 explanation using ML techniques and data scraping. 

&nbsp;

<a name="sys"></a>
### System Permissions and Requirements:
The extension requires access to the current webpage to detect and process user input.


> **Internet Access:** The extension requires an internet connection to fetch data from the Reddit API, perform data scraping, and access other online sources for pseudo-r/ELI5 generation.
> **Chrome Web Browser:** `eli5-chrome` is a Google Chrome extension, and users must have the Chrome browser installed to use it.
> **Chrome Extension Installation:** Users need permissions to install and enable the extension on their Chrome browsers to utilize `eli5-chrome`'s functionality.
> **Local Storage Access:** The extension requires permission to access Chrome's local storage to store user preferences and cache frequently accessed terms for improved performance.

> Put
> Shit
> Here


<a name="user"></a>
### User Permissions and Requirements:
The extension requires access to the current webpage to detect and process user input.


> **Hovering over Words/Phrases:**
> - Users can interact with the extension by simply hovering the cursor over a word or phrase on any webpage to trigger the ELI5 explanation pop-up.
> **Allowing Extension Installation:**
> - Users must have permission to install Chrome extensions. This permission allows users to enable the `eli5-chrome` extension on their Chrome browsers.
> **Providing Internet Access:**
> - Users should ensure their devices have an active internet connection to access r/ELI5 and other online sources for generating pseudo-r/ELI5 explanations.
> **No Personal Data Collection:**
> - `eli5-chrome` does not collect or store any personal user data. Users can rest assured that their browsing activities and interactions with the extension remain private.
> **Feedback and Reporting:**
> - Users are encouraged to provide feedback, report bugs, and suggest improvements through the extension's interface or the project's GitHub repository.
> **Responsible Use:**
> - Users are expected to use the extension responsibly and not engage in any activities that violate Reddit's terms of service or involve any malicious intent.
> **Open Source Contribution:**
> - While not a requirement, users interested in contributing to the project's development can follow the guidelines provided in the project's repository.

> Put
> Shit
> Here


<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------

<a name="use"></a>
## Usage

If a term/phrase has been queried on r/ELI5, users can view relevant comments sorted by Reddit's "top" mechanism. For terms not yet queried on r/ELI5, the extension generates pseudo-r/ELI5 explanations using machine learning techniques and data scraping.

The extension sources its knowledge directly from the r/ELI5 subreddit, renowned for its community-driven ELI5 explanations that break down complicated subjects into easily digestible nuggets of knowledge. When hovering over a word/phrase, the extension provides a little drop-down widget containing the ELI5 definition. The widget promptly vanishes when the mouse moves away, ensuring an unobtrusive browsing experience.

However, the wonders of `eli5-chrome` do not end there. For terms that have already been queried on r/ELI5, the extension goes a step further by presenting snippets of the top-rated comments, curated through Reddit's "top" sorting mechanism. This ensures users receive insights from diverse perspectives and in-depth understanding of the term's context.

But what about terms that have not been previously queried on r/ELI5? `eli5-chrome` does not leave users empty-handed. Leveraging state-of-the-art Machine Learning (ML) techniques, the extension generates auto-generated pseudo-r/ELI5 explanations. Through data scraping and intelligent algorithms, `eli5-chrome` composes ELI5-style definitions, mimicking the subreddit's signature simplicity even for previously unexplored concepts.

### Potential Use Cases and Applications:

> Put
> Shit
> Here

<a name="pre"></a>
### Prerequisites:

> Put
> Shit
> Here

<a name="inst"></a>
### Installation:

1. Download the extension from the Chrome Web Store or the project's GitHub repository.
2. Open Google Chrome and go to "chrome://extensions".
3. Enable "Developer mode" in the top-right corner.
4. Click "Load unpacked" and select the extension folder on your local machine.
5. The `eli5-chrome` extension will be added to Chrome.

   
> Put
> Shit
> Here

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------

<a name="feat"></a>
## Key Features 

> Put
> Shit
> Here

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------
<a name="give"></a>
## How and Why to Contribute

Contributions to `eli5-chrome` are encouraged and welcomed! Here's how you can contribute:

- **Bug Reports:** Report any issues, bugs, or errors you encounter while using the extension.
- **Feature Requests:** Suggest new features or improvements to enhance the extension's functionality.
- **Code Contributions:** Contribute to the development of new features or bug fixes by creating pull requests.
- **Documentation:** Help improve the README.md or add more detailed documentation to the project.


By contributing to `eli5-chrome`, you can make the internet a more accessible and informative place for users of all ages and backgrounds.


We invite you to contribute to `eli5-chrome`'s growth and make the internet a more comprehensible space.\
Whether you report bugs, suggest improvements, or contribute to the open-source development, your participation empowers others to gain knowledge with ease.\
Together, we can transform `eli5-chrome` into an indispensable tool for fostering a culture of accessible and simplified learning across the internet.


> Put
> Shit
> Here

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------
<a name="plus"></a>

## Potential Enhancements

> Put
> Shit
> Here

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------------
<a name="conc"></a> 
## Conclusion

`eli5-chrome` aims to bridge the gap between complex terminology and easy comprehension for all users. By utilizing the power of community-driven explanations from r/ELI5 and cutting-edge ML techniques, this extension can become an invaluable tool for individuals seeking simple yet accurate insights into challenging concepts. With the support and collaboration of contributors, we can make `eli5-chrome` an indispensable resource for internet users worldwide. Let's simplify knowledge and promote understanding together!


Embark on a journey of knowledge exploration with `eli5-chrome` today and witness the power of simplified explanations at your fingertips.\
Simplify the complex, and empower learning through `eli5-chrome`!

<p align="right">(<a href="#eli5">back to top</a>)</p>
---

<a name="lic"></a>
<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------------
<a name="contact"></a>
<!-- CONTACT -->
## Contact

Your Name - [@lyndskg](https://twitter.com/lyndskg) - lyndsey.gu@gmail.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------------
<a name="ack"></a>
<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

> Put
> Shit
> Here

<p align="right">(<a href="#eli5">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/

