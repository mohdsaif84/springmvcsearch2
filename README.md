# 🔍 Search Application using Spring MVC (RedirectView)

A simple Spring MVC based **Search Application** that demonstrates how to redirect user input to an external URL (Google Search) using **RedirectView**.  
This project is designed to clearly explain **Spring MVC request flow**, controller handling, and redirection mechanism.

---

## 📌 Project Description

This application contains a search box where users can enter any keyword.  
After submitting the form, the request is handled by a Spring MVC controller and redirected to Google Search using `RedirectView`.

The project focuses on:
- Understanding **Spring MVC architecture**
- Handling form data using `@RequestParam`
- Performing external URL redirection
- Clean separation of Controller and View (JSP)

---

## 🛠️ Technologies Used

- Java
- Spring MVC
- JSP (Java Server Pages)
- Apache Tomcat 9
- HTML5
- CSS3
- Bootstrap 4

---

## 📂 Project Structure (Exact as per Code)

```text
springmvcsearch2
 ├── src
 │   └── main
 │       ├── java
 │       │   └── springmvcsearch2
 │       │       └── SearchController.java
 │       │
 │       ├── resources
 │       │
 │       └── webapp
 │           ├── WEB-INF
 │           │   ├── views
 │           │   │   └── home.jsp
 │           │   │
 │           │   ├── spring-servlet.xml
 │           │   └── web.xml
 │           │
 │           └── index.jsp
 │
 ├── images
 │   ├── 1-home-page.png
 │   ├── 2-search-ui.png
 │   ├── 3-search-input.png
 │   └── 4-google-result.png
 └── README.md


<img width="965" height="674" alt="Image" src="https://github.com/user-attachments/assets/64173cb0-7dc5-44c4-8192-4a9244ff588b" />

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/60d23662-acab-4c30-8b31-6edbda59d6cd" />

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/8d4569aa-9430-4e09-958a-3715da6cb3f8" />

<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/a8d98ad0-ef33-4e6a-ac81-669a9a5e7147" />










