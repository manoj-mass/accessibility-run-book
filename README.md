# Web Accessibility Run Book. (WIP: Cooking something good here :rocket: :de: )

## Introduction

### Purpose of the run book

The purpose of a web accessibility run book is to serve as a comprehensive and organized reference guide that helps individuals and teams within an organization ensure that websites and web applications are accessible to people with disabilities. It plays a vital role in promoting and maintaining web accessibility by providing clear guidance, processes, and resources. 

### Importance of web accessibility

 - The increasing importance of digital accessibility in today's digital landscape.
 - The impact of inaccessible websites on people with disabilities.
 - The legal and ethical obligations of the organization to provide accessible web content.

### Target audience

This run book is intended to cater to a diverse set of roles within the organization.
 - Developers
 - Designers
 - Content creators
 - Quality assurance teams
 - Managers and decision-makers


### Scope of the Document:

This run book covers best practices, tools, and processes for web accessibility but does not delve into specific coding languages or technologies."

## Legal and Compliance Requirements

Legal and compliance requirements related to web accessibility vary depending on the jurisdiction and the specific regulations that apply. However, there are some common standards and laws that are often referenced in the context of web accessibility. Below, I'll provide detailed information on some of the key legal and compliance requirements that organizations should consider:

1. Americans with Disabilities Act (ADA):

    **Overview:** The ADA is a U.S. federal law that prohibits discrimination on the basis of disability. Title III of the ADA applies to places of public accommodation, including websites and online services.
    
    **Requirements:** Title III of the ADA requires that websites and web applications be accessible to people with disabilities. While the ADA itself does not specify technical standards, it often references the Web Content Accessibility Guidelines (WCAG) as a recognized standard for web accessibility.

2. Section 508 of the Rehabilitation Act:

    **Overview:** Section 508 is a U.S. federal law that requires federal agencies to ensure that their electronic and information technology (including websites) is accessible to people with disabilities.
    
    **Requirements:** Section 508 adopts the WCAG as the technical standard for web accessibility. It outlines specific requirements for various web elements, such as text alternatives, keyboard accessibility, and more. Compliance with Section 508 is mandatory for federal agencies and organizations receiving federal funding.

3. Web Content Accessibility Guidelines (WCAG):

    **Overview:** WCAG is an internationally recognized set of guidelines developed by the World Wide Web Consortium (W3C). It provides detailed recommendations for making web content more accessible.
    
    **Requirements:** WCAG is not a law itself but is often referenced in web accessibility regulations. It consists of three conformance levels (A, AA, and AAA) and four principles: perceivable, operable, understandable, and robust. Organizations often aim for at least Level AA compliance, which includes criteria related to text alternatives, keyboard accessibility, color contrast, and more.

4. European Union Web Accessibility Directive:

    **Overview:** The EU Web Accessibility Directive is a European regulation that requires public sector websites and mobile applications to be accessible to all users, including those with disabilities.
    
    **Requirements:** The directive requires compliance with the European standard EN 301 549, which is based on WCAG 2.1. Public sector organizations in EU member states must ensure their websites and apps meet the specified accessibility requirements.

5. Accessibility Laws in Other Jurisdictions:

    Various countries and regions have their own accessibility laws and regulations. For example, Canada has the Accessible Canada Act, and Australia has the Disability Discrimination Act. These laws may have specific requirements related to web accessibility, and organizations operating in these regions must adhere to them.
    
6. Accessibility Statements and Reporting:

    In addition to meeting technical standards, many regulations require organizations to provide accessibility statements or Voluntary Product Accessibility Templates (VPATs). These documents communicate the level of accessibility achieved and the steps taken to ensure accessibility.

7. Penalties for Non-Compliance:

    Legal consequences for non-compliance with accessibility regulations can include fines, legal action, reputational damage, and loss of business opportunities. Organizations should be aware of the potential penalties for failing to meet accessibility requirements.

It's crucial for organizations to research and understand the specific legal and compliance requirements that apply to their situation. Compliance with these regulations is not only a legal obligation but also a moral and ethical responsibility to ensure equal access to information and services for all individuals, regardless of their disabilities. Organizations should consult with legal experts who specialize in web accessibility to ensure full compliance with the applicable laws and standards.

## Roles and Responsibilities

1. Accessibility Coordinator/Manager:

    **Role:** Oversees and coordinates all web accessibility efforts within the organization.
    
    **Responsibilities:**
      - Develops and maintains accessibility policies and standards.
      - Collaborates with different teams to ensure accessibility is integrated into all web projects.
      - Manages accessibility audits and evaluations.
      - Provides training and guidance on accessibility best practices.
      - Ensures compliance with accessibility laws and standards.
      - Acts as a point of contact for accessibility-related inquiries and issues.

2. Web Developers:

    **Role:** Responsible for implementing accessible code and functionality on the website or web application.
    
    **Responsibilities:**
      - Write HTML, CSS, and JavaScript with accessibility in mind.
      - Implement ARIA (Accessible Rich Internet Applications) roles and attributes as needed.
      - Conduct regular accessibility testing during development.
      - Address and remediate accessibility issues identified during testing.
      - Ensure keyboard navigation and focus management are properly implemented.

3. Web Designers/UI Designers:

    **Role:** Create visually appealing and accessible user interfaces.
    
    **Responsibilities:**
      - Design layouts with responsive and inclusive design principles.
      - Choose accessible color palettes with sufficient color contrast.
      - Specify font styles and sizes that are readable for all users.
      - Design accessible forms, buttons, and other interactive elements.
      - Collaborate with developers to ensure designs are implemented accessibly.

4. Content Creators/Writers:

    **Role:** Produce web content that is accessible and understandable to all users.
    
    **Responsibilities:**
      - Write clear and concise content.
      - Provide alternative text (alt text) for images and multimedia.
      - Use semantic HTML elements for structuring content.
      - Ensure that links and headings are descriptive.
      - Follow plain language and readability guidelines.

5. Quality Assurance/Testers:

    **Role:** Verify and validate that the website meets accessibility requirements.
    
    **Responsibilities:**
      - Conduct comprehensive accessibility testing using various tools and assistive technologies.
      - Document and report accessibility issues.
      - Work with developers to verify issue resolution.
      - Perform regression testing to ensure that accessibility fixes do not introduce new issues.

6. Project Managers:

    **Role:** Ensure that accessibility is considered in project planning and execution.

    **Responsibilities:**
      - Include accessibility requirements in project specifications, DODs, and timelines.
      - Allocate resources for accessibility testing and remediation.
      - Monitor progress and ensure that accessibility goals are met.
      - Facilitate communication between different teams and stakeholders.

7. Legal/Compliance Team:

    **Role:** Ensure that the organization complies with accessibility laws and standards.

    **Responsibilities:**
      - Stay updated on accessibility regulations and requirements.
      - Provide guidance on legal compliance.
      - Assist in preparing accessibility statements and VPATs (Voluntary Product Accessibility Templates).
      - Address legal inquiries or complaints related to web accessibility.

8. End Users:

    **Role:** Provide feedback and report accessibility issues.
    
    **Responsibilities:**
      - Inform the organization about accessibility barriers encountered while using the website.
      - Report accessibility issues through designated channels.
      - Participate in user testing and surveys to provide valuable insights.

Clearly defining these roles and responsibilities and ensuring that team members understand their roles is crucial for effective web accessibility management within an organization. Collaboration and communication among these roles are essential for achieving and maintaining web accessibility.

## Accessibility Testing Tools

Accessibility testing tools are software applications or browser extensions that assist developers, designers, and testers in evaluating and improving the accessibility of websites and web applications. These tools help identify accessibility issues, suggest remedies, and ensure that web content is accessible to people with disabilities. Here are some popular accessibility testing tools:

1. Screen Readers:

    **JAWS (Job Access With Speech):** JAWS is a widely used commercial screen reader for Windows that provides speech and braille output. It is often used by blind and visually impaired individuals.
    **NVDA (NonVisual Desktop Access):** NVDA is a free, open-source screen reader for Windows. It offers support for various languages and is highly customizable.
    **VoiceOver:** VoiceOver is the built-in screen reader for Apple's macOS and iOS devices. It provides speech and braille output and is essential for testing accessibility on Apple platforms.

2. Browser Extensions:

    **axe DevTools (for Chrome and Firefox):** axe DevTools is a browser extension that integrates with web developer tools to analyze web pages for accessibility issues. It provides detailed issue reports and recommendations.

    **WAVE Evaluation Tool (for Chrome and Firefox):** The WAVE browser extension identifies accessibility errors and suggests solutions. It offers a visual representation of accessibility issues directly on web pages.

    **axe Coconut (for Chrome):** axe Coconut is another browser extension powered by axe-core that focuses on testing web components, providing detailed reports and guidance for fixing issues.

    **Screen Reader (chrome vox)** Tool by google. The Chrome Screen reader extension is a showcase of a fully featured screen reader for the web built using only web technologies such as html and javascript.  This extension specifically works within the Chrome browser to read content aloud. For more comprehensive solutions, they recommend the use of full system screen readers like ChromeVox on Chrome OS, VoiceOver on Mac, JAWS, NVDA or Narrator on Windows, etc. 

3. Automated Testing Tools:

    **axe-core:** axe-core is an open-source JavaScript library for automating accessibility testing. It can be integrated into various testing frameworks, such as Selenium and Cypress, to test web applications programmatically.

    **Pa11y:** Pa11y is an open-source command-line tool that allows you to automate accessibility testing and generate reports. It supports multiple output formats and can be used in continuous integration pipelines.

    **Tenon.io:** Tenon is a cloud-based accessibility testing tool that offers both automated and manual testing options. It provides detailed reports and integrations with various development environments.


4. Online Web Accessibility Evaluation Tools:

    **WAVE Web Accessibility Evaluation Tool:** In addition to its browser extension, WAVE also offers an online tool that allows you to enter a URL and receive an accessibility evaluation of the entire webpage.

    **WebAIM's WAVE Web Accessibility Evaluation Tool:** WebAIM offers a free online tool similar to the WAVE tool mentioned above. It provides detailed accessibility reports and explanations of issues.

5. Color Contrast Checkers:

    **Color Contrast Analyzer (CCA):** CCA is a standalone desktop tool for Windows and macOS that helps you check the color contrast of text and background elements to ensure they meet WCAG's color contrast requirements.

    **WebAIM's Color Contrast Checker:** WebAIM offers an online tool to check the color contrast of text elements on a webpage.

6. Keyboard Testing:

    **Keyboard shortcuts and manual testing:** While not a tool in the traditional sense, testing website functionality using only a keyboard is a critical accessibility practice. Ensure that all interactive elements can be operated and navigated using keyboard input alone.

Remember that no single tool can catch all accessibility issues, so it's advisable to use a combination of these tools, manual testing, and user testing with people with disabilities to ensure a high level of web accessibility compliance. Additionally, it's important to regularly update these tools and stay informed about changes in web accessibility standards and guidelines.


## Testing Procedures

Testing procedures for web accessibility are a crucial part of ensuring that a website or web application is accessible to people with disabilities. Here's a detailed breakdown of testing procedures that you can include in your web accessibility run book:

1. Testing Tools and Environment Setup:

   - Begin by outlining the tools and software needed for accessibility testing. Mention any specific browsers, screen readers, or testing  frameworks that your team should use.
   - Provide instructions for setting up the testing environment, including how to configure assistive technologies like screen readers.

2. Testing Scope and Objectives:

   - Define the scope of your accessibility testing. Specify which web pages or components you intend to test.
   - Clarify the objectives of each testing session. Are you looking for specific issues, such as keyboard navigation problems or missing alt text on images?

3. Test Cases and Scenarios:

   - Create a comprehensive list of test cases and scenarios that cover various aspects of web accessibility. This should include tests for different disabilities (e.g., visual, auditory, motor) and different types of content (e.g., text, images, forms).

- Example test cases might include:
    - Testing keyboard navigation through the entire website.
    - Checking for proper heading structure and semantic HTML.
    - Verifying that form fields have accessible labels and error messages.
    - Testing multimedia elements for captions and transcripts.

4. Manual Testing:

   - Explain how to conduct manual accessibility tests, including steps for each test case.
   - Provide guidelines on how to use keyboard navigation to interact with the website.
   - Detail how to use screen readers to review the content and identify issues.
   - Describe the process for checking color contrast and ensuring it meets accessibility standards.

5. Automated Testing:

   - Introduce automated testing tools and their role in accessibility testing.
   - Explain how to run automated tests and interpret the results.
   - Emphasize that automated tools are a complement to, but not a replacement for, manual testing.

6. Responsive Design and Mobile Accessibility:

   - Include testing procedures for responsive design and mobile accessibility.
   - Explain how to use mobile screen readers and testing tools for mobile devices.
   - Address specific mobile accessibility concerns, such as touch targets and viewport settings.

7. Forms and Interactivity:

   - Detail how to test interactive components like forms, buttons, and modal dialogs for accessibility.
   - Provide guidance on using ARIA (Accessible Rich Internet Applications) attributes to enhance interactivity for screen reader users.

8. Media Accessibility:

   - Cover testing procedures for audio and video content, including checking for captions, audio descriptions, and transcripts.
   - Explain how to test multimedia elements with screen readers and assistive technologies.

9. Documenting and Reporting Issues:

   - Outline the process for documenting accessibility issues encountered during testing.
   - Specify the information that should be included in issue reports, such as the location of the issue, a description of the problem, and steps to reproduce it.
   - Provide guidance on using issue tracking systems if applicable.

10. Testing Iteration:

    - Emphasize the importance of iterative testing throughout the development lifecycle.
    - Explain how to verify that issues have been resolved and conduct regression testing to ensure new changes do not introduce new accessibility problems.

11. User Testing:

    - If user testing with people with disabilities is part of your accessibility testing process, provide instructions on how to conduct user testing sessions.
    - Include guidelines for recruiting participants, setting up test environments, and gathering feedback.

12. Accessibility Testing Checklist:

    - Consider including a checklist summarizing the key testing procedures and steps for quick reference.

13. Validation and Compliance:

    - Explain how to validate the website's compliance with specific accessibility standards (e.g., WCAG).
    - Describe the criteria for determining if a web page or application meets accessibility requirements.

14. Testing Frequency:

    - Suggest a testing schedule, such as regular testing before major releases and ongoing testing as new content or features are added.

15. Training and Skill Development:

    - Encourage continuous learning and skill development for the testing team. Provide resources and training materials for testers to improve their accessibility testing expertise.

16. Communication and Collaboration:

    - Stress the importance of effective communication between testers, developers, designers, and content creators to address and resolve accessibility issues.

 ## Web Accessibility Guidelines
