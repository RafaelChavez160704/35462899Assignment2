<p><b>Student ID:</b> 35462899</p> 
<p><b>Student Name:</b> Rafael Gilberto Chavez Castro</p>

<p><b>Domain name:</b> www.rcdesign202x.com</p>

___________________________________________________________________ 

<h1>Assignment 2: Cloud Project & Video Explainer</h1> 

<h2>Introduction</h2>

<p>For this assignment, I created a professional online portfolio to showcase all my graphic design projects in a portfolio website using Amazon EC2 as IaaS, share each of their respective creative processes, and reflect on them. For context, before studying my Bachelor of Information Technology at Murdoch University, I completed a Certificate III, IV, and a Diploma of Graphic Design at North Metropolitan TAFE. Over those years, I created a wide range of design projects, such as logotypes, branding packages and identities, mockup websites, magazine and book covers, digital illustrations, 3D models, and even animations using Adobe software like Illustrator, InDesign, PhotoShop, and AfterEffects, as well as blender, Visual Studio Code, and many others.</p>

<p>This project serves two main purposes: First, to present the work I developed during my graphic design studies in a cohesive and visually appealing format; and second, to demonstrate my ability to apply the technical skills gained in my IT degree so far by hosting this website on Amazon EC2, thus gaining hands hands-on experience and giving me greater control over server management, deployment, and scalability. The portfolio website features a home page introducing me and my creative background, a gallery section organizing my work by category (e.g., branding, typography, UI/UX, illustration), and a contact page with links to my professional profiles (e.g., LinkedIn) and resume. I aim to design the site with responsiveness, accessibility, and user experience in mind, showcasing both my design sensibility and growing web development skills.</p>

<h2>Development Process</h2>

<h3>How did I set up my web server?</h3>

<p>I started by creating an account on Amazon Web Services (AWS). After that, I navigated to the EC2 dashboard and clicked the "Launch Instance" button, which initiated the process of setting up a virtual server in the cloud. I selected the Ubuntu Server 20.04 LTS image marked as "Free Tier Eligible" and opted for the t2.micro instance type, which is part of the AWS Free Tier and sufficient for basic web server tasks. I left all the settings at their defaults, including the storage, which was automatically allocated by the system at a size of 8 GB.</p>

<p>After that, I created a group called "ssh-and-web," since Amazon Web Services already included a rule for SSH that allows me to connect to my instance using an SSH client. After reviewing my setup, I clicked on the "Launch" button. Amazon Web Services then asked whether I wanted to use an existing key pair or create a new one. I chose the second option, named the key pair, and downloaded the generated .pem file. Because this key cannot be replaced or recovered if lost, I made sure to save it both in the cloud and on my computer.</p>

<p>Finally, I clicked "Launch Instance" and used the "View Instances" button to monitor the status of my instance. After confirming that the instance state showed it was running and all status checks passed, my EC2 server was officially live and ready for further configuration and SSH access.</p>

<img width="774" alt="image" src="https://github.com/user-attachments/assets/b9600d4e-2cc4-44e5-bee7-5ac9a1f52bcd" />

<h2></h2>

<img width="776" alt="image" src="https://github.com/user-attachments/assets/86760dee-c131-445e-8173-9c09d84a3ae9" />

<h2></h2>

<img width="771" alt="image" src="https://github.com/user-attachments/assets/e886738e-1ab5-4204-95cf-0c242826bf78" />

<h2></h2>

<img width="771" alt="image" src="https://github.com/user-attachments/assets/d5451552-a447-4d7d-8a50-6fe1ffb513d5" />

<h3>Instance Summary for my web server:</h3>

<img width="949" alt="image" src="https://github.com/user-attachments/assets/440edf0d-f077-423a-9081-cee35e12cc59" />

<h2></h2>

<img width="948" alt="image" src="https://github.com/user-attachments/assets/0b107440-7d9a-47c5-ac78-701baac3bf4a" />




<h3>How did I link it with a DNS entry?</h3>

<p>...</p>

<img width="983" alt="image" src="https://github.com/user-attachments/assets/918db9b3-6a96-49cc-8a96-05734c649af6" />
