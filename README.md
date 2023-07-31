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
    <li>
      <a href="#tech">Technologies and Programming Languages</a>
      <ul>
        <li><a href="#rec">Recommended</a></li>
        <li><a href="#built">Built With</a></li>
        <li><a href="#devenv">Development Environment</a></li>
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
    <li>
      <a href="#start">Getting Started</a></li>
      <ul>
        <li><a href="#xcode">SwiftUI in XCode</a></li>
        <li><a href="#cpp">C++ in CLion</a></li>
        <li><a href="#swift">Swift in CLion</a></li>
      </ul>
    </li>
    <li><a href="#flow">Basic Workflow</a></li>
    <li><a href="#io">Basic I/O Details</a></li>
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
  
> Unleash the ~Audio Amplification Adventure~
> 

---------------------------

<a name="view"></a>
## Project Overview

Have you ever found yourself stumbling upon perplexing terminologies while browsing articles, forums, or research papers? `eli5-chrome` is here to bridge the comprehension gap, making knowledge more accessible to users of all ages and backgrounds.\

Whether you are a curious student, an avid learner, or someone who simply wants to delve into unfamiliar subject matter, `eli5-chrome` empowers you to effortlessly comprehend the most intricate topics the internet has to offer.


`eli5-chrome` is implemented as a Google Chrome extension that provides users with ELI5 (*"Explain Like I'm 5"*) definitions and descriptions of words or phrases on the web.


Drawing inspiration from the immensely popular subreddit *r/ELI5*, this extension equips users with a newfound understanding of intricate jargon by effortlessly displaying simplified explanations upon hovering over challenging words or phrases.
> The extension sources its knowledge directly from the r/ELI5 subreddit, renowned for its community-driven ELI5 explanations that break down complicated subjects into easily digestible nuggets of knowledge.


### <ins>For terms not yet queried on r/ELI5...</ins>
The extension leverages state-of-the-art Machine Learning (ML) techniques &mdash; auto-generating pseudo-"r/ELI5" explanations.
  - Through data scraping and intelligent algorithms, `eli5-chrome` composes ELI5-style definitions, mimicking the subreddit's signature simplicity even for previously unexplored concepts.
    
### <ins>If a term/phrase has, in fact, already been queried on r/ELI5...</ins>
Users can view relevant snippets derived from top-rated comments curated through Reddit's various sorting mechanisms.
  - __<ins>Note</ins>:__ By default, `eli5-chrome` will provide both its ML-generated definition as well information it aggregates from r/ELI5.\
  - By default, `eli5-chrome` will utilize Reddit's "top" sorting mechanism for comments.\
  - This ensures users receive insights from diverse perspectives and in-depth understanding of the term's context.
These configurations can be changed in `eli5-chrome`'s user settings.

When hovering over a word/phrase, the extension provides a little drop-down widget containing the ELI5 definition.\
The widget promptly vanishes when the mouse moves away, ensuring an unobtrusive browsing experience.


### UI/UX
`eli5-chrome` offers an intuitive and user-friendly interface, seamlessly blending into the browsing experience.\
The extension's efficient storage management ensures quick access to previously queried terms, enhancing response times for recurrent usage.\
Moreover, user privacy and data protection are at the forefront, as the extension does not collect or store any personal information, ensuring a secure and trustworthy environment.


<a name="obj"></a>
### <ins>Objectives</ins>
The main objective of `eli5-chrome` is to provide macOS users with a playful solution to amplify their audio volume beyond the limitations imposed by Apple. 

By offering a user-friendly interface and a humorous touch, `eli5-chrome`` aims to enhance the audio experience for users who desire louder sound without compromising on quality.

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------

<a name="tech"></a> 
## Technologies and Programming Languages


<a name="rec"></a> 

### Recommended:
>
> For the *front-end* and *UI* development, the following technologies and programming languages are recommended:
> - **<ins>Swift</ins>:** As the primary language for macOS app development.
> - **<ins>SwiftUI</ins>:** To create a modern and visually appealing minimalistic user interface.


For the *back-end* and audio processing, the following library can be considered:
> - **<ins>Core Audio</ins>:** For audio manipulation and volume boosting.

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
> The time required for completing `volume_vault` can vary based on the developer's expertise and the desired level of polish. 
> 
> - For a *basic* version with the primary features, it may take around 2-4 weeks. 
> - For a *more refined* version with additional features and thorough testing, it may take up to 6-8 weeks or more.

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

1. **<ins>UI Design</ins>:**
    - Design a simple and visually appealing user interface, considering both the menu bar widget and standalone application.
2. **<ins>Implement Volume Boosting</ins>:**
    - Integrate Core Audio to enable volume boosting beyond Apple's pre-set maximum volume.
3. **<ins>Configure UI Controls</ins>:**
    - Add sliders, buttons, or other controls to allow users to adjust the volume and enable/disable the volume boost.
4. **<ins>Menu Bar Integration</ins>:**
    - Implement the functionality to run the application as a menu bar widget with a dropdown interface.
5. **<ins>Standalone Application</ins>:**
    - Create a separate standalone application with the same functionality and minimal UI.
6. **<ins>User Preferences</ins>:**
    - Allow users to customize settings, such as preferred volume levels or startup behavior.
7. **<ins>Testing</ins>:**
    - Perform rigorous testing to ensure smooth functionality and handle potential edge cases.
8. **<ins>Code Optimization</ins>:**
    - Refine the codebase and optimize performance for a seamless user experience.
9. **<ins>Deployment</ins>:**
    - Prepare the application for distribution on the Mac App Store.

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------
<a name="start"></a>

## Getting Started


<a name="xcode"></a>
### <ins>Version 1: XCode in *SwiftUI*</ins>
- [ ] 1. **<ins>Install XCode</ins>:**
> Download and install XCode, the integrated development environment for macOS app development, from the Mac App Store.
- [ ] 2. **<ins>Create a New macOS SwiftUI Project</ins>:**
> Set up a new project and define the basic UI elements and application structure.



<a name="cpp"></a>
### <ins>Version 2: CLion in *C++*</ins>
- [ ] 1. **<ins>Create a New C++ Project</ins>:**
> In CLion, create a new C++ project, and define the basic structure for the VolumeVault application.
- [ ] 2. **<ins>Choose a Cross-Platform Framework (Optional)</ins>:**
> To ensure cross-platform compatibility, consider using a cross-platform C++ framework, such as `Qt` or `wxWidgets`, for the front-end development.\
> These frameworks will allow you to create a user-friendly interface that works seamlessly on macOS and other platforms.
- [ ] 3. **<ins>Integrate Core Audio (macOS-specific)</ins>:**
> To enable volume boosting on macOS, you'll need to use the Core Audio framework.\
> While Core Audio is macOS-specific, you can use preprocessor directives to handle platform-specific code and ensure the application compiles correctly on macOS.
- [ ] 4. **<ins>Implement Minimalistic UI</ins>:**
> Using your preferred C++ framework or native macOS APIs, create a simple and intuitive user interface for `volume_vault`.\
> Keep the UI minimalistic to achieve a clean and user-friendly design.
- [ ] 5. **<ins>Handle macOS Permissions</ins>:**
> When using `Core Audio` to intercept audio output, ensure your application handles macOS permissions gracefully.\
> In some cases, additional permissions may be required from the user to manipulate audio output.
- [ ] 6. **<ins>Code and Test</ins>:**
> Write the logic for volume boosting and user interface interactions.\
> Test the application thoroughly, especially on macOS, to ensure it functions as expected.
- [ ] 7. **<ins>Project Build</ins>:**
> Set up build configurations for macOS in CLion to generate a macOS executable.\
> For cross-platform compatibility, you can also set up build configurations for other target platforms, if applicable.
- [ ] 8. **<ins>Optional XCode or VSCode Integration</ins>:**
> If you prefer, you can use XCode or VSCode for specific tasks, such as advanced debugging, profiling, or specific macOS-related development.\
> You can import your C++ project from JetBrains CLion into XCode or VSCode when necessary.


<a name="swift"></a>
### <ins>Version 3: CLion in *Swift*</ins>
- [ ] 1. **<ins>Swift Support</ins>:**
> By default, JetBrains CLion doesn't provide built-in support for Swift.\
> However, you can enable Swift support using the Swift Plugin.\
>
> To do this, go to "Settings" (or "Preferences" on macOS) > "Plugins" > "Marketplace," search for "Swift," and install the Swift plugin.
- [ ] 2. **<ins>Create a New Swift Project</ins>:**
> After enabling the Swift plugin, you can create a new Swift project in JetBrains CLion.\
> Choose the appropriate project template for a macOS application.
- [ ] 3. **<ins>Minimalistic UI</ins>:**
> Design a simple and user-friendly interface for VolumeVault.\
> SwiftUI, a modern UI framework for Swift, can be used for creating a minimalistic UI that integrates seamlessly with macOS.
- [ ] 4. __<ins>Core Audio Integration (*macOS-specific*)</ins>:__
> To enable volume boosting on macOS, you'll need to integrate `Core Audio`.\
> `Core Audio` is macOS-specific, so you may need to handle platform-specific code using preprocessor directives, ensuring the application compiles correctly on macOS.
- [ ] 5. **<ins>Handle macOS Permissions</ins>:**
> When using `Core Audio` to intercept audio output, ensure your application handles macOS permissions gracefully.\
> In some cases, additional permissions may be required from the user to manipulate audio output.
- [ ] 6. **<ins>Code and Test</ins>:**
> Write the logic for volume boosting and user interface interactions in Swift.\
> Test the application thoroughly, especially on macOS, to ensure it functions as expected.
- [ ] 7. **<ins>Project Build</ins>:**
> Set up build configurations for macOS in CLion to generate a macOS executable.\
> Ensure that the build settings include Swift support.
- [ ] 8. **<ins>Optional XCode or VSCode Integration</ins>:**
> If you prefer, you can use XCode or VSCode for specific tasks, such as advanced debugging, profiling, or specific macOS-related development.\
> You can import your Swift project from JetBrains CLion into XCode or VSCode when necessary.

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------
<a name="flow"></a>
## Basic Workflow Guide

1. Upon launching `volume_vault`, the user is presented with a clean and straightforward UI, either as a menu bar widget or a standalone application.
2. The user can toggle the volume boost feature on/off using a button or checkbox.
3. A slider allows the user to adjust the level of volume boost they desire, ranging from 0% to 2000%.
4. The application utilizes Core Audio to intercept audio output and apply the desired volume boost.
5. The boosted audio is then sent to the system's audio output for playback.
6. The user can control the volume directly from the application or the menu bar widget.

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------

<a name="io"></a>
## Basic I/O Details

### Input:
> - User interaction with the application's sliders and buttons to control volume boost and other settings.
> 
>
### Output:
> - Boosted audio output to the system's audio playback.

&nbsp;

### System/User Permissions and Requirements:
To manipulate audio output, `volume_vault` will need appropriate permissions to access the user's audio settings and intercept audio playback. 

Users will need to grant the necessary permissions during the application's first run.\
`volume_vault` should adhere to macOS security guidelines and handle permissions gracefully.

> Put
> Shit
> Here

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------

<a name="use"></a>
## Usage

If a term/phrase has been queried on r/ELI5, users can view relevant comments sorted by Reddit's "top" mechanism. For terms not yet queried on r/ELI5, the extension generates pseudo-r/ELI5 explanations using machine learning techniques and data scraping.

The extension sources its knowledge directly from the r/ELI5 subreddit, renowned for its community-driven ELI5 explanations that break down complicated subjects into easily digestible nuggets of knowledge. When hovering over a word/phrase, the extension provides a little drop-down widget containing the ELI5 definition. The widget promptly vanishes when the mouse moves away, ensuring an unobtrusive browsing experience.

However, the wonders of ELI5 Explorer do not end there. For terms that have already been queried on r/ELI5, the extension goes a step further by presenting snippets of the top-rated comments, curated through Reddit's "top" sorting mechanism. This ensures users receive insights from diverse perspectives and in-depth understanding of the term's context.

But what about terms that have not been previously queried on r/ELI5? ELI5 Explorer does not leave users empty-handed. Leveraging state-of-the-art Machine Learning (ML) techniques, the extension generates auto-generated pseudo-r/ELI5 explanations. Through data scraping and intelligent algorithms, ELI5 Explorer composes ELI5-style definitions, mimicking the subreddit's signature simplicity even for previously unexplored concepts.

### Potential Use Cases and Applications:
- **<ins>Media Playback</ins>:**
  - Enhance audio volume when watching movies, videos, or listening to music.
- **<ins>Video Conferencing</ins>:**
  - Improve audio clarity during online meetings and conferences.
- **<ins>Accessibility</ins>:**
  - Assist users with hearing impairments by increasing the volume as needed.
- **<ins>Noisy Environments</ins>:**
  - Allow users to boost volume in loud or noisy surroundings.

> Put
> Shit
> Here

### Prerequisites:

> Put
> Shit
> Here

### Installation:

> Put
> Shit
> Here

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------

<a name="feat"></a>
## Key Features 

- **<ins>Volume Boosting</ins>:**
  - Amplify audio playback volume by up to 2000% beyond Apple's default limits.
- **<ins>Minimalistic UI</ins>:**
  - A simple and user-friendly interface with essential controls.
- **<ins>Menu Bar Widget</ins>:**
  - Run the application as a convenient menu bar drop-down widget.
- **<ins>Standalone Application</ins>:**
  - Offer the option to use `volume_vault` as a standalone application for easy access.
- **<ins>Customizability</ins>:**
  - Allow users to fine-tune the volume boost level according to their preferences.

> Put
> Shit
> Here

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------
<a name="give"></a>
## How and Why to Contribute

- **Contribution Guidelines:** Provide clear guidelines on how developers can contribute to `volume_vault`.
- **Open Source:** Consider making `volume_vault` an open-source project to foster community contributions.
- **Bug Reports and Feature Requests:** Encourage users to submit bug reports and suggest new features to improve the application.

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

1. **<ins>Equalizer</ins>:**
   
Implement an audio equalizer to provide users with further control over audio frequencies.


2. **<ins>Presets</ins>:**
   
Include preset configurations for different scenarios (*e.g.*, movies, music, gaming) for quick adjustments.


3. **<ins>Audio Effects</ins>:**

Integrate audio effects like spatial audio or surround sound to enrich the audio experience.


4. **<ins>Dark Mode</ins>:**

Add support for macOS dark mode to enhance visual appeal and consistency with macOS aesthetics.

> Put
> Shit
> Here

<p align="right">(<a href="#eli5">back to top</a>)</p>

---------------------------
<a name="conc"></a> 
## Conclusion


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

