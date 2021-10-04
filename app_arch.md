# [SAS App for Volumetric Capture Processing](https://teamz-comp523.github.io/vcp/index.html) 

| [Project](https://teamz-comp523.github.io/vcp/project.html) | [Team](https://teamz-comp523.github.io/vcp/team.html) | [Journal](https://teamz-comp523.github.io/vcp/journal.html) | [Deliverables](https://teamz-comp523.github.io/vcp/deliverables.html)

## Application Architecture
### PostgreSQL hosting on AWS for data persistence
- Summary – In order to store data persistently, we decided to use PostgreSQL. 
- Problem – We need to make the data persistent because project data should appear on the page after the user re-login. We need to store all users ’ uploaded videos and related files in the Cloud.
Constraints – We have a bunch of solutions available in hand: MySQL, SQLite, MongoDB, and PostgreSQL. As for MySQL and MongoDB, it is hard to implement and maintain. SQLite and PostgreSQL are both viable. Our client suggests PostgreSQL.
- Options – 
- Rationale – We select PostgreSQL for our application based on its reliability, stability, scale, and security as well as our client’s preference.

### UI and front end: ReactJS
- Summary – In order to design a user-friendly user interface, we decided to use the ReactJS framework.
- Problem – This app requires us to present plenty of similar designed responsive interactive components. Since React components encapsulate states, we can efficiently update and render the right components when the data changes.
Constraints – Our application may not render correctly on Safari browser.
- Options – ReactJS, Angular, Vue
- Rationale – React JS is better than Angular or Vue JS because of its superior Virtual DOM capabilities, its robust community support, rich documentation, its light-weight attributes, manageable learning curve, and its flexibility to allow mobile functionality with React Native’s.

### Programming language
- Summary – In order to integrate with the Django backend, React frontend and provide the best user experience, we decided to use JavaScript and Python as our main programming language.
- Problem – We need to use a language that is most compatible with our frontend framework (React) and backend framework (Django). We also need a language that is well supported in the web environment that can handle both front and backend well. We also need a language that can provide a great user experience and a code base that is easy to manage.
- Constraints – The constraint is our client expects us to build a native web application to store, upload and download files. The other constraint is that we have to build the frontend and the backend from scratch and integrate them together.
Options – We could use some other popular languages such as Java, C, C++, etc. to write our programs. However, for building a user-friendly UI, we want to use React for the frontend since it allows our app to run on multiple platforms and the application we create will be clean and easy to use. Besides, since we are integrating our backend with AWS S3 for uploading, downloading and storing. Django would be a better choice than Spring since it is a more mature framework than Spring.
- Rationale – Our frontend, React, is programmed in JavaScript and our backend, Django, is programmed in Python and requested by our client. This will make the backend-frontend integration much smoother and easier. JavaScript is most commonly used in web development. With Django, we are able to get rapid action development, Great community, as well as open source features. It is easier to read and learn. Therefore we picked JavaScript and Python.