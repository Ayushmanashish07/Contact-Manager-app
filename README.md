<p align="center"><h1 align="center">CONTACT-MANAGER-APP</h1></p>
<p align="center">
	<em><code>A straightforward phonebook management system built with a RESTful CRUD API layered on a Node.js backend, using MongoDB for data storage. The app allows users to create, read, update, and delete contact entries through well-defined API endpoints.</code></em>
</p>
<p align="center">
	<!-- Shields.io badges disabled, using skill icons. --></p>
<p align="center">Built with the tools and technologies:</p>
<p align="center">
	<a href="https://skillicons.dev">
		<img src="https://skillicons.dev/icons?i=express,nodejs,mongodb,npm,postman">
	</a></p>
<br>

## 🔗 Table of Contents

- [📍 Overview](#-overview)
- [👾 Features](#-features)
- [📁 Project Structure](#-project-structure)
  - [📂 Project Index](#-project-index)
- [🚀 Getting Started](#-getting-started)
  - [☑️ Prerequisites](#-prerequisites)
  - [⚙️ Installation](#-installation)
  - [🤖 Usage](#🤖-usage)
  - [🧪 Testing](#🧪-testing)
- [📌 Project Roadmap](#-project-roadmap)
- [🔰 Contributing](#-contributing)
- [🎗 License](#-license)
- [🙌 Acknowledgments](#-acknowledgments)

---

## 📍 Overview

<code>Contact-Manager-app is a lightweight backend application built with Node.js and MongoDB for managing contacts. 
It provides a RESTful API that supports CRUD operations — allowing users to create, read, update, and delete 
contact information efficiently. The project follows a modular architecture with separate layers for controllers, 
routes, models, and middleware, making it easy to extend and maintain. Ideal for learning REST API development 
and backend fundamentals with JavaScript.</code>

---

## 👾 Features

<code><b>Features:</b><br>
• CRUD Operations – Create, Read, Update, and Delete contacts through RESTful API endpoints.<br>
• MongoDB Integration – Stores and manages contact data in a scalable NoSQL database.<br>
• Modular Project Structure – Separate controllers, models, routes, and middleware for clean code organization.<br>
• Configuration Support – Includes config and constants for easy setup and customization.<br>
• Lightweight & Extendable – Simple core functionality, making it easy to add authentication, validation, or a frontend later.
</code>

---

## 📁 Project Structure

```sh
└── Contact-Manager-app/
    ├── config
    │   └── dbConnection.js
    ├── constant.js
    ├── controllers
    │   ├── contactController.js
    │   └── userController.js
    ├── middleware
    │   ├── errorHandler.js
    │   └── validateTokenHandler.js
    ├── models
    │   ├── contactModel.js
    │   └── userModel.js
    ├── package-lock.json
    ├── package.json
    ├── routes
    │   ├── contactRoutes.js
    │   └── userRoutes.js
    └── server.js
```


### 📂 Project Index
<details open>
	<summary><b><code>CONTACT-MANAGER-APP/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/package-lock.json'>package-lock.json</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/constant.js'>constant.js</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/package.json'>package.json</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/server.js'>server.js</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- config Submodule -->
		<summary><b>config</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/config/dbConnection.js'>dbConnection.js</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- controllers Submodule -->
		<summary><b>controllers</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/controllers/userController.js'>userController.js</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/controllers/contactController.js'>contactController.js</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- models Submodule -->
		<summary><b>models</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/models/contactModel.js'>contactModel.js</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/models/userModel.js'>userModel.js</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- routes Submodule -->
		<summary><b>routes</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/routes/contactRoutes.js'>contactRoutes.js</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/routes/userRoutes.js'>userRoutes.js</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- middleware Submodule -->
		<summary><b>middleware</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/middleware/validateTokenHandler.js'>validateTokenHandler.js</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Ayushmanashish07/Contact-Manager-app/blob/master/middleware/errorHandler.js'>errorHandler.js</a></b></td>
				<td><code>❯ REPLACE-ME</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

---
## 🚀 Getting Started

### ☑️ Prerequisites

Before getting started with Contact-Manager-app, ensure your runtime environment meets the following requirements:

- **Programming Language:** JavaScript
- **Package Manager:** Npm


### ⚙️ Installation

Install Contact-Manager-app using one of the following methods:

**Build from source:**

1. Clone the Contact-Manager-app repository:
```sh
❯ git clone https://github.com/Ayushmanashish07/Contact-Manager-app
```

2. Navigate to the project directory:
```sh
❯ cd Contact-Manager-app
```

3. Install the project dependencies:


**Using `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ npm install
```




### 🤖 Usage
Run Contact-Manager-app using the following command:
**Using `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ npm start
```


### 🧪 Testing
Run the test suite using the following command:
**Using `npm`** &nbsp; [<img align="center" src="https://img.shields.io/badge/npm-CB3837.svg?style={badge_style}&logo=npm&logoColor=white" />](https://www.npmjs.com/)

```sh
❯ npm test
```


---
## 📌 Project Roadmap

<p>
<b>Project Roadmap:</b><br>
1. <b>Phase 1:</b> Setup Node.js server and MongoDB connection <br>
2. <b>Phase 2:</b> Implement CRUD operations for managing contacts <br>
3. <b>Phase 3:</b> Add modular structure with controllers, routes, and middleware <br>
4. <b>Phase 4:</b> Introduce error handling and request validation <br>
5. <b>Phase 5:</b> Add user authentication and authorization <br>
</p>


---

## 🔰 Contributing

- **💬 [Join the Discussions](https://github.com/Ayushmanashish07/Contact-Manager-app/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/Ayushmanashish07/Contact-Manager-app/issues)**: Submit bugs found or log feature requests for the `Contact-Manager-app` project.
- **💡 [Submit Pull Requests](https://github.com/Ayushmanashish07/Contact-Manager-app/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/Ayushmanashish07/Contact-Manager-app
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/Ayushmanashish07/Contact-Manager-app/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=Ayushmanashish07/Contact-Manager-app">
   </a>
</p>
</details>

---

## 🎗 License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

## 🙌 Acknowledgments

<p>
<b>Acknowledgements:</b><br>
• Special thanks to the open-source community for providing tools and libraries that made this project possible.<br>
• Inspired by common backend project structures and REST API best practices.<br>
• Thanks to Node.js and MongoDB documentation for guidance in building scalable applications.<br>
• Gratitude to fellow developers and mentors who share knowledge and tutorials that helped shape this project.
</p>


---
