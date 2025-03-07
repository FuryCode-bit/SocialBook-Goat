# SocialBook-Goat

![Contributors][contributors-shield] ![Stargazers][stars-shield] ![MIT License][license-shield] ![LinkedIn][linkedin-shield]

<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://github.com/FuryCode-bit/SocialBook-Goat">
    <img src="readme/ua.png" alt="Logo" height="80">
  </a>

  <h3 align="center">Totally Secure Social Network (or is it?)</h3>

  <p align="center">
    <br />
    <a href="https://github.com/FuryCode-bit/SocialBook-Goat"><strong>Explore the docs »</strong></a>
    <br />
  </p>
</div>

---

## About The Project

![Project Screenshot][project-screenshot]

### Objective

This project was developed as part of **Assignment 3 - A Goat Social Network** for the *Analysis and Exploration of Vulnerabilities* course in the Cybersecurity Master's program at the University of Aveiro.

The goal was to explore software vulnerabilities from a developer’s perspective. Students were tasked with introducing carefully designed security flaws into an existing social media web application while maintaining its core functionality.

### Assignment Overview

This project focuses on intentionally introducing and analyzing security vulnerabilities from a developer's perspective. As part of the assignment, the following elements have been implemented:

- The application features a `/security` endpoint that provides a list of identified vulnerabilities.
- The following security vulnerabilities have been deliberately introduced:
  - **Information Leakage**: Exposing sensitive data unintentionally.
  - **Cross-Site Scripting (XSS)**: Allowing malicious scripts to execute in a user's browser.
  - **Server-Side Template Injection (SSTI)**: Enabling remote code execution via template rendering.
  - **SQL Injection**: Manipulating database queries to access unauthorized data.
  - **Cryptographic Failures**: Weak encryption or improper cryptographic implementations.
  - **Identification and Authentication Failures**: Weak or misconfigured authentication mechanisms leading to unauthorized access.

These vulnerabilities were added while ensuring that the application remains functional, following the assignment guidelines.

### Base Application Features

SocialBook-Goat is a Django-based social media web app with built-in security flaws. It includes:

- **User Profiles**: Registration, login, and profile customization.
- **Post Sharing**: Users can create and delete posts.
- **Likes & Follows**: Engage with posts and follow users.
- **Chat Functionality**: Direct messaging between users.
- **CI/CD Integration**: Jenkins-based automation pipeline for testing and deployment.

> **Disclaimer:** This application is intentionally insecure for educational purposes. **Do not deploy in a production environment.**

## Getting Started

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/FuryCode-bit/SocialBook-Goat.git
   ```
2. Navigate to the project directory:
   ```sh
   cd SocialBook-Goat
   ```
3. Create a virtual environment and activate it:
   ```sh
   python -m venv env
   source env/bin/activate
   ```
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
5. Apply database migrations:
   ```sh
   python manage.py migrate
   ```
6. Start the development server:
   ```sh
   python manage.py runserver
   ```
7. Access the app at [http://localhost:8080](http://localhost:8080)

## Team Members

The following members contributed to the development of this project:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/FuryCode-bit">
        <img src="https://avatars2.githubusercontent.com/u/62396294?s=400&u=7017c42401bedbcc13df785146962b6cd128e658&v=4" width="100px;" alt="Marco Bernardes"/><br>
        <sub>
          <b>Marco Bernardes</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/joelvaz0x01">
        <img src="https://avatars.githubusercontent.com/u/65792406?v=4" width="100px;" alt="Joel Vaz"/><br>
        <sub>
          <b>Joel Vaz</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/rlopes0773">
        <img src="https://avatars.githubusercontent.com/u/68201862" width="100px;" alt="Ruben Lopes"/><br>
        <sub>
          <b>Ruben Lopes</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/silvatiago1">
        <img src="https://avatars.githubusercontent.com/u/92639775?v=4" width="100px;" alt="Tiago Silva"/><br>
        <sub>
          <b>Tiago Silva</b>
        </sub>
      </a>
    </td>
    <!--<td align="center">
      <a href="#">
        <img src="https://miro.medium.com/max/360/0*1SkS3mSorArvY9kS.jpg" width="100px;" alt="Foto do Steve Jobs"/><br>
        <sub>
          <b>Steve Jobs</b>
        </sub>
      </a>
    </td>-->
  </tr>
</table>

## License

Distributed under the **Apache License**. See `LICENSE` for details.


[contributors-shield]: https://img.shields.io/github/contributors/FuryCode-bit/SocialBook-Goat.svg?style=for-the-badge
[contributors-url]: https://github.com/FuryCode-bit/SocialBook-Goat/graphs/contributors
[stars-shield]: https://img.shields.io/github/stars/FuryCode-bit/SocialBook-Goat.svg?style=for-the-badge
[stars-url]: https://github.com/FuryCode-bit/SocialBook-Goat/stargazers
[license-shield]: https://img.shields.io/github/license/FuryCode-bit/SocialBook-Goat.svg?style=for-the-badge
[license-url]: https://github.com/FuryCode-bit/SocialBook-Goat/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/bernardeswebdev
[project-screenshot]: readme/goat.png





