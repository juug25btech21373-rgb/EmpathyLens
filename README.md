# EmpathyLens – Accessibility Awareness Prototype

## 1. Project Overview

[EmpathyLens_Prototype .pdf](https://github.com/user-attachments/files/34524591/EmpathyLens_Prototype.pdf)

**EmpathyLens** is a web-based accessibility awareness prototype designed to help developers understand the challenges faced by blind and visually impaired users when interacting with websites using screen readers.

A website may look visually appealing and easy to navigate, but that does not necessarily mean it is accessible to everyone. Elements such as buttons without meaningful names, form fields without labels, and images without alternative text can make navigation difficult for people who rely on assistive technologies.

EmpathyLens demonstrates these challenges through a guided, interactive experience. It allows users to explore a sample website, understand how certain elements may be announced by a screen reader, identify example accessibility issues, and compare an initial interface with an improved version.

The main objective is to encourage developers to think beyond visual appearance and consider accessibility while designing and developing websites.

## 2. Problem Statement

Many websites are designed primarily around visual appearance. Developers often focus on colours, layouts, typography, and visual interactions without considering how users who rely on screen readers experience the same interface.

For example:

- A button containing only an icon may not communicate its purpose to a screen-reader user.
- A form field without a properly associated label may be difficult to identify.
- An image without meaningful alternative text may not communicate its information.
- Poor semantic HTML can make page structure and navigation harder to understand.

These issues can create barriers for people who use assistive technologies.

There is a need for a simple and interactive way to help developers understand these accessibility challenges and recognize the importance of inclusive web design.

## 3. Proposed Solution

EmpathyLens addresses this awareness gap through a guided seven-step demonstration.

The prototype introduces a fictional user persona named Yasmin, who uses a screen reader while interacting with a job application website.

Through this scenario, developers can explore how inaccessible interface elements may affect a user's experience.

The prototype demonstrates:

1. An introduction to web accessibility and the user scenario.
2. Uploading, pasting, or selecting an HTML example.
3. A scripted screen-reader-style simulation.
4. Example accessibility findings.
5. An improved HTML example.
6. A before-and-after comparison.
7. A final accessibility awareness message.

By presenting these stages in one interface, EmpathyLens makes accessibility concepts easier to understand through practical examples.

## 4. Objectives

- Raise awareness about web accessibility.
- Demonstrate challenges experienced by users who rely on screen readers.
- Explain the importance of meaningful accessible names and form labels.
- Encourage the use of semantic HTML.
- Demonstrate how small improvements can make interfaces easier to understand.
- Promote inclusive and user-centred web development.

## 5. Key Features

### 5.1 Guided Seven-Step Experience

The prototype provides a structured journey that introduces accessibility concepts and gradually demonstrates common website accessibility challenges.

### 5.2 HTML Input and Preview

Users can:

- Upload an HTML file.
- Paste their own HTML code.
- Load a built-in sample HTML example.
- Preview the HTML in an isolated iframe.

This allows users to explore how an HTML interface appears visually.

### 5.3 Screen-Reader-Style Simulation

The prototype includes a scripted demonstration of how certain interface elements might be announced by a screen reader.

It illustrates the difference between unclear controls and controls with meaningful accessible names.

**Note:** This is a scripted simulation, not an actual screen reader. It does not connect to assistive technology or read uploaded HTML automatically.

### 5.4 Example Accessibility Findings

The findings screen demonstrates common accessibility issues, including:

- Buttons without meaningful accessible names.
- Missing or unclear form labels.
- Images without alternative text.

It also presents suggested improvements to help developers understand how these issues can be addressed.

### 5.5 Improved HTML Example

An improved sample demonstrates the use of:

- Meaningful button labels.
- Properly associated form labels.
- Descriptive image alternative text.
- Appropriate HTML input types.
- More understandable interface elements.

### 5.6 Before-and-After Comparison

The prototype presents an illustrative comparison between the initial and improved examples.

It highlights how clearer labels and accessible names can improve the understanding of interface controls.

### 5.7 Developer Reflection

A reflection area allows users to think about how they would approach accessibility when designing and developing websites.

### 5.8 Theme Toggle

Users can switch between light and dark themes.

### 5.9 Responsive Interface

The layout adjusts to different screen sizes, making the prototype usable on desktop, tablet, and mobile devices.

## 6. Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure and content of the application |
| CSS3 | Styling, layout, themes, and responsive design |
| JavaScript | Navigation, interactions, HTML preview, and scripted demonstrations |
| iframe | Isolated preview of HTML examples |

The project is implemented using vanilla HTML, CSS, and JavaScript without requiring a frontend framework or backend server.

## 7. How the Prototype Works

The application follows a simple front-end workflow.

**Step 1 – Introduction**

Users are introduced to the accessibility problem and the fictional user scenario.

**Step 2 – HTML Selection**

Users can upload an HTML file, paste HTML code, or load the provided example.

**Step 3 – Visual Preview**

The selected HTML is displayed inside a sandboxed iframe.

**Step 4 – Screen-Reader-Style Demonstration**

Users explore pre-written announcements illustrating how unclear controls may be communicated to screen-reader users.

**Step 5 – Example Findings**

The application displays sample accessibility issues and possible improvements.

**Step 6 – Improved Example**

Users explore an improved HTML example containing more descriptive labels and controls.

**Step 7 – Comparison and Reflection**

Users compare the initial and improved examples and reflect on the importance of accessibility.

## 8. Project Structure

The GitHub repository can be organized as follows:

```text
EmpathyLens/
│
├── index.html
├── prototype.png
└── README.md
```

### File Description

- **index.html** – Contains the complete frontend implementation, including HTML structure, CSS styling, and JavaScript functionality.
- **prototype.png** – Screenshot of the EmpathyLens prototype interface.
- **README.md** – Project documentation describing the problem, solution, features, technologies, implementation, and limitations.

## 9. Installation and Usage

EmpathyLens does not require a complex installation process.

### Option 1 – Run Locally

1. Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Open the downloaded project folder.

3. Locate `index.html`.

4. Open the file in a modern web browser.

### Option 2 – Run Using VS Code

1. Open the project folder in Visual Studio Code.
2. Open `index.html`.
3. Run it using a browser or the Live Server extension.

No backend setup, database configuration, or package installation is required.

## 10. Current Implementation and Limitations

EmpathyLens is currently a **frontend concept and awareness prototype**.

The following limitations should be considered:

- The project does not include a backend or database.
- There is no user authentication or login system.
- Uploaded HTML is previewed locally within the browser.
- The screen-reader-style demonstration uses predefined transcripts.
- The example accessibility findings are fixed sample data.
- Findings are not automatically calculated from uploaded HTML.
- The comparison values are illustrative and are not based on actual accessibility testing.
- The project does not integrate with real screen-reader software.
- The reflection field is temporary and is not permanently stored.
- The prototype does not provide a complete WCAG compliance assessment.

These limitations are intentional within the scope of the current demonstration.

## 11. Future Enhancements

The project can be extended with the following features:

- Integration with actual accessibility testing tools.
- Automatic detection of missing labels and accessible names.
- Real screen-reader integration and testing workflows.
- More detailed WCAG-based accessibility checks.
- Interactive keyboard navigation demonstrations.
- Improved feedback based on user-provided HTML.
- Backend integration for saving user projects and progress.
- More user personas representing different accessibility needs.
- A more comprehensive accessibility evaluation dashboard.

These enhancements could help transform EmpathyLens from an awareness prototype into a more functional accessibility evaluation platform.

## 12. Expected Impact

EmpathyLens aims to encourage developers to recognize that accessibility is an essential part of web development.

By demonstrating how seemingly small HTML issues can affect the usability of a website, the project encourages developers to:

- Consider users with different abilities.
- Use semantic HTML correctly.
- Provide meaningful labels and alternative text.
- Design interfaces that support assistive technologies.
- Make inclusive design an important part of development from the beginning.

The project promotes the idea that a good website should not only look good but should also be understandable and usable by everyone.

## 13. Conclusion

EmpathyLens demonstrates the importance of designing websites with accessibility in mind.

Through a guided experience, sample HTML interfaces, scripted screen-reader-style demonstrations, example findings, and before-and-after comparisons, it helps developers understand accessibility challenges from a different perspective.

Although the current version is a frontend awareness prototype rather than a fully automated accessibility checker, it establishes a foundation for further development into a more comprehensive accessibility-focused platform.
