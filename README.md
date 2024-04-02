
# Super_Hero_Resume

<img align="right" src="https://github.com/SurajPatil29/Assignment_Project_1/assets/148176329/4c0d2824-b5ab-4ac6-a475-de2272038d34" width="150px" height="150px">

The project "Super_Hero_Resume" is a captivating static website dedicated to showcasing the illustrious profile of the superhero Daredevil, leveraging the fundamental web technologies HTML and CSS. This project provides a comprehensive and interactive online platform to explore various facets of Daredevil's character, including his backstory, abilities, equipment, and notable adversaries, all encapsulated within a visually appealing and user-friendly design

<h2>Screenshot</h2>
    <h2>Using Media Query Dynamic view</h2>
    <div>
        <div align=left>
            <h3>2560Pixel</h3>
            <img src="https://github.com/SurajPatil29/Assignment_Project_1/assets/148176329/df1564b2-c622-46ce-8666-03cb7cd353e2" alt="" width="50%">
        </div>
        <div align=right>
            <h3>1440Pixel</h3>
            <img src="https://github.com/SurajPatil29/Assignment_Project_1/assets/148176329/4f56272c-777e-438a-82db-c076db38b507" alt="" width="50%">
        </div>
        <div align=left>
            <h3>1024Pixel</h3>
            <img src="https://github.com/SurajPatil29/Assignment_Project_1/assets/148176329/fe25062a-9c42-4161-80d8-72eaa93ae61e" alt="" width="50%">
        </div>
        <div align=right>
            <h3>425Pixel</h3>
            <img src="https://github.com/SurajPatil29/Assignment_Project_1/assets/148176329/116d61be-6300-4be8-bc1a-2b24f46be0fc" alt="" width="50%">
        </div>
    </div>


## Demo

https://bejewelled-peony-e826b5.netlify.app/

## Features

- Responsive Navigation: The site features a fixed top navigation bar (#navbar) and a dynamic dropdown (select element) for mobile responsiveness, facilitating easy access to different sections of the resume: About, Abilities & Weapon, Rivals, and Videos.

- Responsive Navigation: The site features a fixed top navigation bar (#navbar) and a dynamic dropdown (select element) for mobile responsiveness, facilitating easy access to different sections of the resume: About, Abilities & Weapon, Rivals, and Videos.

- Hero Introduction: A dedicated section (#about) enriched with audio narratives and textual content outlines Daredevil's origin story, his transformation into the vigilante protector of Hell's Kitchen, and significant milestones in his life and career as a lawyer and superhero.

- Profile Overview: This segment displays Daredevil's profile photo alongside crucial personal information such as height, weight, gender, eye and hair color, place of origin, education, public identity, powers, weapon of choice, and suit specialty, providing a snapshot of his physical and professional attributes.

- Abilities and Weaponry: A detailed presentation (#abbilities and #wepones) visualized through a table and progress bars highlights Daredevil's superior physical and combat skills, alongside a showcase of his iconic weapon, the multi-functional baton.

- Formidable Rivals: The website portrays Daredevil's top adversaries (#rivels), including Kingpin and Gladiator, through vivid images and descriptions, emphasizing the intense rivalries and challenges faced by our hero.

- Multimedia Integration: The #video section embeds YouTube videos, offering a glimpse into Daredevil's thrilling action sequences and story arcs, enriching the user experience with engaging visual content.

- Contact and Creator Information: The site concludes with a personal touch, providing contact details and social links (#profile) of the project's creator, fostering a connection between the creator and the audience

### General Style and Aesthetics
- Theme and Color Scheme: The webpage uses a dark theme with a background image (BG1.jpg), which suggests a potentially moody, atmospheric, or intense theme, depending on the image content. Text and other elements are primarily white, providing contrast against the dark background. The navbar has a distinct dark red (rgb(83, 8, 8)) background color, consistent with the overall dark theme.
- Typography: Arial, Helvetica, and sans-serif are chosen for the font family, offering a clean, modern, and highly legible typeface that works well for digital screens.
### Layout and Structure
- Navigation Bar (#navbar):Positioned as fixed, ensuring it stays visible as the user scrolls. It uses flex display to evenly space links, enhancing navigability. The navigation bar becomes invisible (display: none) under certain screen widths, replaced by #navbar1 in responsive designs, adapting to mobile or narrower viewports.
- Content Sections: The use of flex display in various sections (e.g., #contact, #discription, #tableInfo, and #video) suggests a flexible and responsive layout that adjusts according to the screen size, improving the user experience on different devices.
- Responsive Design: The CSS contains media queries targeting different viewport widths, adjusting the layout, visibility of elements (such as the navigation bar), and sizing of images and other content to ensure the webpage is accessible and user-friendly across a range of devices, from desktops to mobile phones.
### Functionality Highlights
- Interactive Elements: The navigation bar (#navbar) changes the cursor to a pointer on hover, indicating clickable links. Additionally, #profile > a:hover changes the text color and underlines on hover, improving user interaction feedback.
- Adaptive Content: The use of media queries to adapt the webpage's layout and content presentation according to the viewport size significantly enhances functionality. For instance, in narrower viewports, the navigation changes to #navbar1, and content blocks like #rivels and #video shift from side-by-side layouts to stacked layouts for better readability on smaller screens.
- Accessibility and Readability: The choice of high-contrast text color against the background and responsive design elements like scalable text and images helps in making the webpage more accessible and easier to read across various devices and screen sizes.
### Imagery and Multimedia
- The background images (BG1.jpg and BG4.jpg) play a crucial role in setting the visual tone of the website. The choice to use different images at various breakpoints (@media queries) indicates an intention to optimize visual impact across devices.
- Multimedia elements like audio and video (#about>audio and #video>div>iframe) are incorporated, suggesting a rich, interactive user experience. Their responsive adjustments ensure that these elements remain functional and visually consistent across devices.
### Summary
- The CSS design emphasizes a visually engaging, interactive, and responsive user experience. It smartly balances aesthetic appeal with functionality, ensuring the website remains accessible, navigable, and visually consistent across a wide range of devices.


### Lessons Learned

Certainly! Working on this project has provided you with practical experience and insights into several foundational and advanced CSS concepts. Here are the key learnings from each area you mentioned:

### Media Queries
- Adaptive and Responsive Design: You learned how to use media queries to create designs that adapt to different screen sizes, enhancing the user experience across devices. This is crucial for modern web development where users access content on a wide array of devices with varying screen dimensions.
- Syntax and Application: You've grasped how to structure media queries to apply CSS rules under specific conditions, such as min-width and max-width, enabling you to tailor the layout, typography, and navigation for mobile phones, tablets, and desktops.
### Selectors
- Complex Selector Use: Through the use of various selectors, including element, ID (#id), and class (.class) selectors, you've learned to precisely target and style specific parts of the webpage. This is fundamental for creating visually appealing and well-structured web pages.
- Pseudo-classes and Attribute Selectors: The project introduced you to more complex selectors, like :hover for interactive elements, which enhances the user interface by providing visual feedback to user actions.
### Navigation Bar
- Fixed Positioning and Flexbox: Creating a navigation bar that is both fixed and flexible demonstrated the use of CSS positioning and Flexbox layout. This is key for developing user-friendly navigation that remains accessible as users scroll through a page.
- Responsive Design for Navigation: Adjusting the navigation bar for different screen sizes using media queries taught you the importance of responsive design principles in improving the navigability and functionality of webpages on various devices.
### Box Model
- Understanding Margin, Border, Padding, and Content: You've gained a practical understanding of the CSS Box Model, which is crucial for layout design. Knowing how to manipulate these properties allows for precise control over the spacing and alignment of webpage elements.
- Application in Layout and Design: Through practice, you've seen how adjustments to the box model properties can drastically affect the overall look and feel of your design, influencing readability, aesthetics, and user experience.
### Additional Lessons
-Typography and Color Scheme: Choosing fonts and colors that complement the overall design theme while ensuring readability is vital. Your project work emphasized the importance of these elements in creating an aesthetically pleasing and accessible user interface.
- Content Structuring: You've learned about structuring content using HTML and CSS, understanding how to lay out different types of content (text, images, videos) in a way that's both appealing and functional.
### Moving Forward
These learnings are building blocks in web development. As you progress, consider diving deeper into:

- Advanced CSS features like CSS Grid, which offers even more layout control than Flexbox.
- CSS preprocessors such as Sass or Less to write more maintainable and concise CSS.
- CSS animations and transitions to enhance interactivity and user engagement.
Accessibility best practices to ensure your web designs are usable by as wide an audience as possible.
This project has laid a solid foundation. Continue building on these concepts, experimenting with new techniques, and tackling more complex projects to further your understanding and skills in web development.



Insert gif or link to demo


![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)

