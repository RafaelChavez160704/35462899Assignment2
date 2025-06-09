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

<p>First, I created an account on Amazon Web Services. Next, I went to the EC2 dashboard and clicked on the "Launch Instance" button, which started the process of setting up a virtual server in the cloud. From there, I chose the Ubuntu Server 20.04 LTS image labeled as “Free tier eligible” while sticking with t2.micro. (AWS Free Tier, sufficient for basic web server tasks.), ahd left all settings on default, including the storage of the server, which was automatically allocated by the system with a size of 8 GB. After that, I created an "ssh-and-web" group, as Amazon Web Services already included an SSH rule, which allows me to connect to my instance through an SSH client. After reviewing my setup, I clicked on the "Launch" button, and Amazon Web Services asked me if I preferred to select and use an existing key pair or create a new one. I chose the second option, gave it a name, and downloaded the .pem file that was generated afterwards. (Since the key cannot be replaced or recovered if lost, I made sure to save and store it both on the cloud and my computer.)


Finally, click "Launch Instance" to create your EC2 virtual machine. You may see a warning stating that your instance is accessible from the internet; this is expected since it’s intended to function as a public-facing web server. Once launched, use the "View Instances" button to monitor the status of your instance. When the instance state reads “Running” and the status checks pass, your Ubuntu EC2 server is live and ready for SSH access and further configuration.

<img width="774" alt="image" src="https://github.com/user-attachments/assets/b9600d4e-2cc4-44e5-bee7-5ac9a1f52bcd" />


<h3>How did I link it with a DNS entry?</h3>

<p>...</p>

<img width="983" alt="image" src="https://github.com/user-attachments/assets/918db9b3-6a96-49cc-8a96-05734c649af6" />
