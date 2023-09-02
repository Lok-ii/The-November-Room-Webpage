# The-November-Room-Webpage

# <h2>Hosted Link:- https://lok-ii.github.io/The-November-Room-Webpage/dist/index.html</h2>

# Description: 

    HTML Structure (index.html):

        The <!DOCTYPE html> declaration specifies that this is an HTML5 document.
        The <html> element defines the root of the HTML document and specifies the document's language as English (en).
        The <head> section contains metadata and external resource links.
        The <meta> elements define the character set (UTF-8) and the viewport for responsive design.
        The <title> element sets the title of the webpage, which appears in the browser tab.
        External stylesheets and scripts are linked in the <head> section.

  
![Screenshot 2023-09-02 211217](https://github.com/Lok-ii/The-November-Room-Webpage/assets/129180844/a620c936-33d0-4087-9b60-493c2f23605b)

    Navbar:

        The navigation bar is placed within a <nav> element and is given various classes for styling.
        The logo and menu icon are placed within a <div>. The menu icon is initially hidden on larger screens (lg:hidden).
        The social media links (Facebook, Twitter, LinkedIn) are list items within an unordered list (<ul>).
        Each link contains an icon from Font Awesome and a text description.

![Screenshot 2023-09-02 211231](https://github.com/Lok-ii/The-November-Room-Webpage/assets/129180844/658e6c79-fa7c-407a-b9d6-ee7605978e90)

    Home Section:

        The home section is wrapped in a <div> with inline CSS that sets a background image.
        The background image is overlaid with a semi-transparent black background using a <span> element.
        The main content, including a heading and a paragraph, is wrapped in a container <div>.
        The heading "Feel the Power" is displayed using an <h1> element.
        A paragraph describing the gym is provided in a <p> element.
        A button with the text "Download Brochure" is created using an <a> element.
    
![Screenshot 2023-09-02 211243](https://github.com/Lok-ii/The-November-Room-Webpage/assets/129180844/d4e5be17-f444-45bb-9480-3a8229ff1c70)

    About Section:

        The "About" section is defined in a <section> element with the ID "about."
        It consists of two columns within a flex container. The left column holds an image, and the right column contains text.
        The image and text are enclosed in separate <div> elements.
        The text includes a small heading, a larger heading, and a paragraph.
        Three key points with icons are listed below the paragraph.

![Screenshot 2023-09-02 211251](https://github.com/Lok-ii/The-November-Room-Webpage/assets/129180844/d167c593-83f9-43c9-9725-5d2b3c1a1fd7)

    Trainers Section:

        The "Trainers" section is within a <section> element.
        It uses a flex container to display trainer profiles side by side.
        Each trainer's information is enclosed within a <div> with a class specifying the card's width (w-full, md:w-4/12).
        Each card contains an image of the trainer, their name (<h5>), and their role (<p>).

![Screenshot 2023-09-02 211317](https://github.com/Lok-ii/The-November-Room-Webpage/assets/129180844/2c7fd49e-7c1b-4376-b7e9-ad6d068c28f9)

    Contact Header Section:

        The "Contact Header" section is defined within a <section> element with a black background.
        A heading ("Contact Us") and a brief message are displayed.
    
    Contact Form Section:

        This section includes a contact form for user inquiries.
        The form is wrapped in a container <div> with classes for styling.
        Form fields for "Full Name," "Email," and "Message" are enclosed within <input> and <textarea> elements.
        A "Send Message" button is present with a <button> element.

![Screenshot 2023-09-02 211330](https://github.com/Lok-ii/The-November-Room-Webpage/assets/129180844/32857973-89e7-458e-a6ba-d02e3c7a40e9)

    Footer:

        The footer section is enclosed in a <footer> element and contains copyright information.
        It includes a heading, a brief text, and social media icons.
        Social media icons are buttons with Font Awesome icons.
    
    Scripts (script tags at the end of the document):

        The AOS (Animate on Scroll) library is initialized using AOS.init() for scroll-based animations.
        The Font Awesome icon library is loaded using a <script> tag with a provided kit URL.
