## Book My Show Application Clone

Pages:
    >> Home.Page.jsx (Default.Hoc.jsx)
    >> Movie.Page.jsx (Movie.Hoc.jsx)
    >> Play.Page.jsx (Default.Hoc.jsx)

HOCs/Layouts:    
    >> Default.Hoc.jsx 
    >> Movie.Hoc.jsx

Components:
    >> Cast                 Cast.Component.jsx
    >> Entertainment        EntertainmentCard.Component.jsx
    >> HeroCarousel         HeroCarousel.Component.jsx
                            Arrows.Component.jsx
    >> MovieHero            MovieHero.Component.jsx
                            MovieInfo.Component.jsx
    >> Navbar               Navbar.Componenet.jsx
                            MovieNavbar.Component.jsx
    >> PaymenModal          PaymentComponent.jsx
    >> PlayFilters          Filters.Componenet.jsx
    >> Poster               Poster.Componenet.jsx
    >> PosterSlider         PosterSliderComponenet.jsx

npx create-react-app .



https://api.themoviedb.org/3/movie/550?api_key=ccfa4ecd270cd9e26cc5791a495b5aca



## DevOps
Dev => Development Team
Ops => Operation Team

Devops and CICD (Docker & Kubernetes)

Dev ------------------------------------------------------------->  Ops
write code + share code -----------------------------------------> Testing + Scaling, Bug Fixing


Developer Team -> Operation Team -> Testing Team


complexity of appln more => den time to build the appln will be more


Scenario:
    Team of 3 members => Book My Show Appln
        >> All have diff OS (Mac, Windows, Linux)

        Person-1                Person-2                Person-3
        (windows)                (Mac)                    (Linux)
        Packages                   


It works on my m/c


Book My Show Appln (Resources):
RAM: 4GB
ROM: 1TB
GPU: 2GB


## Virtualisation
(I could be able to run virtual OS on my local OS)
Local OS in case of Person -2 => Mac
Virtualisation
Virtual OS => Windos


Basic Arch:

Windows (RAM, ROM, GPU) || Virtual OS
--------------------------------------
OS          || Local OS





Adv Arch:
Windows Virtual OS                 Unix Virtual OS
7Gb, 500GB, 1GB                     3GB, 500GB, 1GB                 || Internal Resource Sharing

Base/Local OS 
8GB, 1TB, 2GB


## Containersation (Docker)

Base:
Windows  Virtual OS (2Gb, 250Gb)                       Unix Virtualisation OS (2GB, 250GB)
                        Docker Engine       (4GB, 500Gb)
Base Local OS  (8GB, 1TB) 


Book My Show Appln (3GB)



Windows  Virtual OS (2Gb, 250Gb)                       Unix Virtualisation OS (2GB, 250GB)
                        Docker Engine       (4GB, 500Gb)
Base Local OS  (8GB, 1TB) 


Docker >> EC2 Instance >> Img and Container



Kubernetes (Orchestra)
>> Nodes >>
            >> Master Node (A person holding stick in Orchestra event | Lead)
            >> Child Node (A group of people who will be following the lead guidance)



NGINX (Light Weight Servers)

AWS >> EC2 (Virtual Machines)
Amazon Elastic Compute Cloud Service




Docker  
        >> Image
        >> Containers

Image(Parent)
Containers(Child) || Server

Client Server Architecture



Kubernetes 
    >> Docker Deamon ---> Server (Initialization)
    >> Docker Client ---> Client
    >> Docker Swarm  --> Orchestra (Master | Main Node | Configuration)

    >> Master Node
    >> Child Node 
            >> POD (Container)
            >> Development (Wher it will keep close eye on Pod)
    

Example: I want to run a server in the docker with 3 container on my book my show clone applns

Docker
    >> Image
            >> Cont 1
            >> Cont 2
            >> Cont 3


Kubernetes
    >>  Masster Node      
            >> Child Node | POD -1
            >> Child Node | POD -2
            >> Child Node | POD -3   



Master Node
        Child Node -1       Child Node -2       Child Node -3               Development


Development: Analayze and manatin all the PODs/Child Nodes/ Servers/ Containers

Docker > Kubernetes




AWS 
    >> Service: EC2 (VM) => Unix OS
    Base OS >> Windows



    Client
                                Kuberntes
    Server

Serv1 (1000req/hr) => 200-300 similar reqs
Proxy Serv1

Client sends req -> Proxy Serv  -> Serv1

Client sends req -> Proxy Serv for Proxy Serv-> Proxy Serv  -> Serv1

NGINX (Light Weight Server)
        >> Reverse Proxy
        >> Load Balancing



# Resume

## Validtaing Resume
https://resumeworded.com/

## Any File Operations on your cv/resume
https://www.ilovepdf.com/compress_pdf

## For Creating Resumes
https://www.canva.com/en_in/

## Sections of Resume
1. Name 
2. Desigation (Full Stack Intern at DevTown | Student | Fresher)
3. Experience/Internship 
4. Contanct Details (Email, Phone No, LinkedIn)
5. Skills
6. Education Qualifications
7. Projects
8. Achievements


Experience/Internship:
Full Stack Intern (MM/YYYY-MM/YYYY) - DevTown
Summary (I got worked here as an Full Stack Intern for so n so period where I explored the Full stack web devlopment with so and so technologies).
Book My Show Clone (1 or 2 lines)
project 2 (1 or 2 lines)



Tester Intern - Wipro


## Building Summary
https://quillbot.com/



# Job Platforms
1. LinkedIn
2. Naukri
3. Indeed
4. CutShort
5. GeekTrust
6. AngelList
7. Monster Jobs
8. Internshala




Additionally Resources, What Next ?, GitHub, Diff Positions
Typescript, DevOps
Payment Gateway Project
One Last Day (Project Submission)
DSA 



## What Next afet Web Tech ?
1. Next.js
2. Three.js
3. Electron (Windows Applicatons)
4. React Native (IOS and Android Applications)
5. GSAP or Framer Motion (Animations)
6. Scaling and DevOps | Sprint Review
7. Testing for React or JS and Advanced Performance 
8. DSA


## Technical Round For Coding Questions?
1. Explain the logic
2. Write the Logic/Code in Brute-Force (Base Level) Approach
3. Later Optimise the code


## Differnent Positions:
1. Software Engineer
2. Software Developer
3. Web Full Stack Developer 
4. Front-end Developers
5. Backend Developers
6. React JS Devlopers
7. Angular Developers
8. NodeJs Developers
9. DBA (Data Base Adminstrator)
9. Automated Testing
10. Manual Tester
11. UI UX Developer
12. Architect



## GitHub
https://rahuldkjain.github.io/gh-profile-readme-generator/




Friday: Payment Gateway & brief out the project
Saturday: Devops & DSA
Sunday: DSA
Monday: Last Day
