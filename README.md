# AuthSystem 🥷🏽🔐 (WIP)

<p align="center">
   <a href="http://makeapullrequest.com"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat" alt=""></a>
   <a href="https://github.com/ayoisaiah/F2/actions"><img src="https://github.com/ayoisaiah/F2/actions/workflows/test.yml/badge.svg" alt="Github Actions"></a>
   <a href="https://golang.org"><img src="https://img.shields.io/badge/Made%20with-Go-1f425f.svg" alt="made-with-Go"></a>
   <a href="https://goreportcard.com/report/github.com/ayoisaiah/f2"><img src="https://goreportcard.com/badge/github.com/ayoisaiah/f2" alt="GoReportCard"></a>
   <a href="https://github.com/ayoisaiah/f2"><img src="https://img.shields.io/github/go-mod/go-version/ayoisaiah/f2.svg" alt="Go.mod version"></a>
   <a href="https://github.com/ayoisaiah/f2/blob/master/LICENCE"><img src="https://img.shields.io/github/license/ayoisaiah/f2.svg" alt="LICENCE"></a>
   <a href="https://github.com/ayoisaiah/f2/releases/"><img src="https://img.shields.io/github/release/ayoisaiah/f2.svg" alt="Latest release"></a>
</p>

A Complete Backend Service with User Authentication and Authorization 

## Description
This repository contains a backend service developed in GoLang that handles user authentication and authorization. 

It includes functionalities like user registration, login, password reset, social authentication (e.g., GitHub, Google, Twitter), and JWT authentication. 

The service is designed with security in mind, implementing measures to prevent common attacks such as SQL injection, CSRF attacks, and brute force attacks.


## Features
- [ ] User Authentication
    - [ ] User Registration: Allows new users to create an account.
    - [ ] User Login: Allows existing users to log in.
- [ ] Session Management
    - [ ] Create Session: Creates a session when a user logs in.
    - [ ] Destroy Session: Destroys the session when a user logs out.
- [ ] Password Management
    - [ ] Password Reset: Allows users to reset their password.
    - [ ] Password Hashing: Hashes passwords before storing them in the database.
- [ ] Social Authentication: Allows users to log in using their social media accounts.
  - [ ] GitHub Authentication: Allows users to log in through GitHub
  - [ ] Google Authentication: Allows users to log in through Google
  - [ ] Personal Authentication: Implementing Personal OAuth in Go for the app
- [ ] JWT Authentication: Uses JSON Web Tokens (JWT) for secure information transmission.
- [ ] Security Measures
    - [ ] SQL Injection Prevention: Prevents SQL injection attacks.
    - [ ] CSRF Prevention: Prevents Cross-Site Request Forgery (CSRF) attacks.
    - [ ] Slowloris Prevention: Prevents Slowloris Attacks


## Contributions
Contributions, issues, and feature requests are welcome!

## License
MIT

