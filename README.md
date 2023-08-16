---

<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a>
    <img src="https://raw.githubusercontent.com/Morvie/Documentation/main/img/logo.png" alt="Logo" width="250" height="250">
  </a>

  <h3 align="center">Documentation</h3>

  <p align="center">
    <br />
    <a href="https://github.com/orgs/Morvie/repositories"><strong>View repositories»</strong></a>
    <br />
    <br />
    <a href="">View Demo</a>
    ·
    <a href="https://github.com/Morvie/Documentation/issues">Report Bug</a>
  </p>
</div>

---

# Maintainer(s) SEP 2022 - JAN 2023
</div>

---

<table align=center>
  <tbody>
    <tr>
     <td align="center"><a><img src="https://avatars.githubusercontent.com/u/58692211?v=4" width="100px;" alt="Mark Goertz"/><br /><sub><b>Mark Goertz</b></a></td>
  </tbody>
</table>

---

# :raising_hand: Introduction
Morvie is an application that allows users to create discussions in forums based on movies like Reddit. It consists of multiple microservices, an API gateway and a frontend. But first of all: let me introduce myself;

My name is Mark Goertz, and I am a student at Fontys HBO-ICT bachelor education at Eindhoven. 
With the sixth semester as the current semester, I am safe to say I do have some knowledge within the software world.

Before this current semester, I performed a software internship at a company. During that time, I gained a lot of software skills and learned to be more professional within the work environment. But also, trouble shooting and finding the best possible solution for the client. And do I have gained a little bit of information about enterprise software; like the concepts and how does non-functional user requirements matter more within these software products.
For this semester, I am willing to learn new programming languages but also already experienced languages. So, that I can develop myself in my skills. The languages I would likely be learning from scratch this semester would be <a><strong>C#</strong> with <strong>.NET6 and JavaScript with React.js.</strong></a> 
My goal would be to pass this semester and go to the next semester with more professionalism and technical knowledge. 

<br/>


### :hammer_and_wrench: Languages and Tools :
These following technologies are used the most frequent amount within this project:
<div align=center>
  <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/react/react-original.svg" title="React" alt="React" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/csharp/csharp-original.svg" title="Csharp" alt="Csharp" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/dotnetcore/dotnetcore-original.svg" title="dotnet" alt="dotnet" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/microsoftsqlserver/microsoftsqlserver-plain-wordmark.svg" title="MySQL"  alt="MySQL" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/docker/docker-original.svg" title="Docker" alt="Docker" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/kubernetes/kubernetes/9884746f0fd338c393d23dbb2a87d118a34fe5e5/logo/logo.svg" title="Kubernetes" alt="Kubernetes" width="60" height="60"/>&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/1119b9f84c0290e0f0b38982099a2bd027a48bf1/icons/github/github-original.svg" title="Git" **alt="Git" width="60" height="60"/>
</div>
<br/>

The following technologies also contribute to this project:
- Ocelot Gateway
- Entity Framework
- Dependabot
- Snyck
- SonarCloud
- Azure
- K6 by Grafana
- Grafana
- Influx DB
- MediatR (CQRS)
- MassTransit

## Software architecture
<img src="https://github.com/Morvie/Documentation/blob/main/img/Level3%5BComponent-diagram%5D.png" height="auto" width="auto">

## CI/CD pipeline
<img src="" height="auto" width="auto">


## API Endpoints (from gateway)
The application has the following endpoints:

HTTP method | API endpoints             | Description
------------|---------------------------|---------------------------
 GET        | /api/v1/movies            | Get all movies
 GET        | /api/v1/movies/{id}       | Get movie by ID
 POST       | /api/v1/movies            | Create movie
 PUT        | /api/v1/movies            | Update movie
 DELETE     | /api/v1/movies/{id}       | Delete movie
 GET        | /api/v1/Forums            | Get all forums
 GET        | /api/v1/Forums/{id}       | Get forum by ID
 POST       | /api/v1/Forums            | Create forum
 PUT        | /api/v1/Forums            | Update forum
 DELETE     | /api/v1/Forums/{id}       | Delete forum



## Contributing
Pull requests are not desired. This was a project for school within my study at Fontys HBO-ICT.

## License
[MIT](https://choosealicense.com/licenses/mit/)
