Aim

To create a college information webpage using ordered lists, unordered lists, nested lists, and description lists in HTML.

Question 1: Write an introduction for the college/course.

Answer:

A college provides students with knowledge, practical skills, and opportunities to develop their careers. The Bachelor of Technology (B.Tech) in Computer Science and Engineering (CSE) is a technical course that focuses on programming, computer systems, software development, and modern technologies. Students learn theoretical concepts and practical skills through lectures, laboratory sessions, and projects.

Question 2: Make a list of departments or subjects using <ul>.

Answer:

The <ul> tag is used to create an unordered list. Each item is written using the <li> tag.

Example:

<h2>Departments and Subjects</h2>

<ul>
    <li>Computer Science and Engineering</li>
    <li>Artificial Intelligence</li>
    <li>Mathematics</li>
    <li>Physics</li>
    <li>Chemistry</li>
    <li>Communication Skills</li>
</ul>

An unordered list displays items with bullet points.

Question 3: Show the admission process using <ol>.

Answer:

The <ol> tag is used to create an ordered list. It displays the steps in a numbered sequence.

Example:

<h2>Admission Process</h2>

<ol>
    <li>Choose the desired course.</li>
    <li>Check the eligibility criteria.</li>
    <li>Fill out the application form.</li>
    <li>Submit the required documents.</li>
    <li>Complete the admission procedure.</li>
    <li>Pay the applicable admission fees.</li>
    <li>Attend the orientation programme.</li>
</ol>

An ordered list is useful for displaying steps that need to be followed in sequence.

Question 4: Arrange topics of any subject in a nested list.

Answer:

A nested list is a list placed inside another list. It is useful for arranging subjects and their topics in a hierarchical structure.

Example:

<h2>Computer Science Subjects and Topics</h2>

<ul>
    <li>Programming
        <ul>
            <li>Introduction to Programming</li>
            <li>Variables and Data Types</li>
            <li>Conditional Statements</li>
            <li>Loops</li>
        </ul>
    </li>

    <li>Web Development
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
        </ul>
    </li>

    <li>Database Management
        <ul>
            <li>Introduction to Databases</li>
            <li>SQL Basics</li>
            <li>Database Tables</li>
        </ul>
    </li>
</ul>

Question 5: Use <dl>, <dt>, and <dd> for details of teachers or courses.

Answer:

The <dl> tag creates a description list. The <dt> tag specifies a term or name, and the <dd> tag provides its description.

Example:

<h2>Course Details</h2>

<dl>
    <dt>B.Tech CSE</dt>
    <dd>
        A technical undergraduate programme focused on
        computer science, programming, and software development.
    </dd>

    <dt>HTML</dt>
    <dd>
        HTML stands for HyperText Markup Language.
        It is used to structure content on web pages.
    </dd>

    <dt>CSS</dt>
    <dd>
        CSS stands for Cascading Style Sheets.
        It is used to style and design web pages.
    </dd>

    <dt>JavaScript</dt>
    <dd>
        JavaScript is a programming language used to
        add interactive features to websites.
    </dd>
</dl>

Question 6: Organize the page through headings and sections.

Answer:

HTML headings such as <h1>, <h2>, and <h3> help organize content into a clear hierarchy. The <section> tag groups related content into separate sections. This makes the webpage easier to read and understand.

Example:

<header>
    <h1>College Information</h1>
</header>

<section>
    <h2>Introduction</h2>
    <p>Information about the college and course.</p>
</section>

<section>
    <h2>Departments</h2>
    <p>List of departments and subjects.</p>
</section>

<section>
    <h2>Admission Process</h2>
    <p>Steps to complete admission.</p>
</section>

Complete HTML Code

Create a file named college-info.html and copy and paste the following code.

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>College Information - B.Tech CSE</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f7fb;
            color: #333;
            line-height: 1.7;
        }

        header {
            background-color: #174ea6;
            color: white;
            text-align: center;
            padding: 25px;
        }

        main {
            max-width: 900px;
            margin: 25px auto;
            padding: 25px;
        }

        section {
            background-color: white;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 8px #00000010;
        }

        h2 {
            color: #174ea6;
        }

        li {
            margin-bottom: 6px;
        }

        dt {
            font-weight: bold;
            color: #174ea6;
            margin-top: 12px;
        }

        dd {
            margin-left: 20px;
        }

        footer {
            background-color: #123b7a;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>

<body>

    <header>
        <h1>College Information</h1>
        <p>Bachelor of Technology - Computer Science and Engineering</p>
    </header>

    <main>

        <section>
            <h2>1. Introduction</h2>

            <p>
                Welcome to the College Information webpage.
                This webpage provides information about the
                B.Tech Computer Science and Engineering course,
                its subjects, admission process, and important topics.
            </p>

            <p>
                Computer Science and Engineering focuses on
                programming, computer systems, software development,
                databases, and web technologies. It helps students
                develop technical knowledge and problem-solving skills.
            </p>
        </section>

        <section>
            <h2>2. Departments and Subjects</h2>

            <p>The following is a sample list of departments and subjects:</p>

            <ul>
                <li>Computer Science and Engineering</li>
                <li>Artificial Intelligence</li>
                <li>Mathematics</li>
                <li>Physics</li>
                <li>Chemistry</li>
                <li>Communication Skills</li>
                <li>Electrical Engineering</li>
            </ul>
        </section>

        <section>
            <h2>3. Admission Process</h2>

            <p>The general admission process includes the following steps:</p>

            <ol>
                <li>Select the desired course.</li>
                <li>Check the eligibility criteria.</li>
                <li>Fill out the application form.</li>
                <li>Submit the required documents.</li>
                <li>Complete the selection or counselling process, if applicable.</li>
                <li>Pay the applicable fees and confirm admission.</li>
                <li>Attend the college orientation programme.</li>
            </ol>
        </section>

        <section>
            <h2>4. Subjects and Nested Topics</h2>

            <ul>
                <li>Programming
                    <ul>
                        <li>Introduction to Programming</li>
                        <li>Variables and Data Types</li>
                        <li>Conditional Statements</li>
                        <li>Loops and Functions</li>
                    </ul>
                </li>

                <li>Web Development
                    <ul>
                        <li>HTML</li>
                        <li>CSS</li>
                        <li>JavaScript</li>
                    </ul>
                </li>

                <li>Database Management
                    <ul>
                        <li>Database Concepts</li>
                        <li>SQL Basics</li>
                        <li>Tables and Relationships</li>
                    </ul>
                </li>
            </ul>
        </section>

        <section>
            <h2>5. Course Details</h2>

            <dl>
                <dt>B.Tech CSE</dt>
                <dd>
                    An undergraduate engineering programme focused on
                    computer science and software technologies.
                </dd>

                <dt>HTML</dt>
                <dd>
                    HyperText Markup Language is used to structure
                    content on web pages.
                </dd>

                <dt>CSS</dt>
                <dd>
                    Cascading Style Sheets is used to style and
                    design web pages.
                </dd>

                <dt>JavaScript</dt>
                <dd>
                    A programming language used to add interactive
                    behaviour to websites.
                </dd>
            </dl>
        </section>

        <section>
            <h2>6. Importance of HTML Lists</h2>

            <p>
                HTML lists help organize information clearly.
                Unordered lists display bullet points, ordered lists
                display numbered steps, nested lists organize topics
                into levels, and description lists display terms
                with their explanations.
            </p>
        </section>

    </main>

    <footer>
        <p>College Information | Assignment 3.3</p>
    </footer>

</body>

</html>

Steps to Run the Webpage

Open Visual Studio Code.

Create a file named college-info.html.

Paste the complete HTML code into the file.

Save the file using Ctrl + S.

Right-click the file and select Open with Live Server, or open it directly in a browser.

Check that all headings, bullet lists, numbered lists, nested lists, and course descriptions are displayed correctly.

Take a screenshot of the working webpage.

Result

A college information webpage was created successfully using HTML. It includes an introduction, unordered lists, an ordered admission process, nested subject lists, description lists, headings, and sections.

Submission

Submit the following:

college-info.html

A screenshot of the webpage displayed in the browser.