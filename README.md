<a name="readme-top"></a>


<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
- [💻 Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
  - [Installation](#installation)
- [Author](#author)
- [Socials](#socials)

<!-- PROJECT DESCRIPTION -->

# 📖 Hello SJA Pathway! <a name="about-project"></a>

**Hello SJA Pathway!** is a simple landing page that greets the SJA Pathway Community. This Project touches on the essential concepts of software engineering such as working with Git, Version Vontrol, Github flow, Pull requests and more.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>


<details>
  <summary>Client</summary>
  <ul>
    <li>HTML</li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li>CSS</li>
  </ul>
</details>

<details>
<summary>Package Manager</summary>
  <ul>
    <li>Node.js</li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>


- Loads up SJA Pathway page



<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Git
- Node.js
- Linters

### Setup

#### Git:

- For MacOS:
    ```sh
    brew install git
    ```

- For Windows:
    ```bash
    curl -L https://git-scm.com/download/win -o Git-Installer.exe && start Git-Installer.exe
    ```

- For Linux:
    ```sh
    sudo apt update && sudo apt install git -y
    ```

#### Node.js:

- For MacOS:
    ```sh
    brew install Node
    ```

- For Windows:
    ```bash
    curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
    sudo apt-get install -y nodejs
    ```

- For Linux:
    ```bash
    curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
    sudo apt-get install -y nodejs
    ```

- For Linters:
    - Add a copy of `.github/workflows/linters.yml`
    - For HTML linter install HTMLhint by running:
        ```bash
        npm install htmlhint --save-dev
        ```
    - Make configurations in `.hintrc` file
    - For CSS linter install stylelint by running:
        ```bash
        npm install --save-dev stylelint stylelint-config-standard stylelint-tree-validator
        ```
    - Make configurations in `.stylehintrc.json` file
    - Run all linting checks:
        ```
        npm run test    
        ```

### Installation

1. Clone the repository
```bash
git clone https://github.com/musaibxandra/Hello-world.git
cd Hello-world
```

2. Set up package.json
```bash
npm init -y
```

<!-- AUTHORS -->

## Author

- Mohammed Maqdoom - [GitHub](https://github.com/musaibxandra)

## Socials

- [LinkedIn](https://linkedin.com/in/musaibxandra)

