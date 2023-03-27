<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [📖 Vet Clinic Database ](#-vet-clinic-database-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Connect to your PostgreSQL server with psql](#connect-to-your-postgresql-server-with-psql)
    - [Create the database](#create-the-database)
    - [Connect to the database](#connect-to-the-database)
  - [👥 Authors ](#-authors-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)

<!-- PROJECT DESCRIPTION -->

# 📖 Vet Clinic Database <a name="about-project"></a>

**Vet Clinic Database** is a Relational database to create the data structure for a vet clinic

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **CREATE DATABASE vet_clinic**
- **CREATE ANIMALS TABLE**
- **QUERY AND UPDATE ANIMALS TABLE**
- **QUERY MULTIPLE TABLES**
- **ADD JOIN TABLE FOR VISITS**
- **DATABASE PERFORMENCE AUDIT**
- **ASS DATABASE SCHEMA DIAGRAM**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- PostgreSQL server installed and running
- psql installed

### Setup

Clone this repository to your desired folder:

Example commands:
  git clone https://github.com/AlexisJW/vet-clinic-database.git
  cd vet-clinic-database

### Connect to your PostgreSQL server with psql
    
```
  psql
```

### Create the database

```
  CREATE DATABASE vet_clinic;
```

### Connect to the database

```
  \c vet_clinic
```

- Use [schema.sql](./schema.sql) to create all tables.
- Use [data.sql](./data.sql) to populate tables with sample data.
- Check [queries.sql](./queries.sql)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

👤 **Didier Peran Ganthier**

- GitHub: [@AlexisJW](https://github.com/AlexisJW)
- LinkedIn: [Jean Walner Alexis](https://linkedin.com/in/jean-walner-alexis)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project, please give it a ⭐️!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- N/A

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./MIT.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
