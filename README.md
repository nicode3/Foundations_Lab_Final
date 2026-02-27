# Foundations_Lab_Final

## Introduction:

My name is Nicolas Pena. I am studying Computer Science and Information Security. My goal is to break into the cyber security industry by landing a SOC Analyst Role. I plan on doing this by completeing industry standard level projects and gaining key certifications.

### Security Foundations: Governance & Frameworks
Kobalt.io. (2024). Blogpost
https://kobalt.io/confidentiality-integrity-and-availability-in-cyber-security/ 
**CIA TRIAD:**
The CIA triad stands for Confidentiality, Integrity and Availability. Each one has its own important purpose in cyber security.
**Confidentiality** in cybersecurity is used to protect the data from prying eyes. Making sure information is only seen by authorized individuals.
**Integrity** in cybersecurity is the standard to make sure no data has been tampered/modified. Data loses integrity when its original form has been altered.
**Availability** in cybersecurity is the security in knowing that the information that is needed for authorized individuals is always ready for use. Not only information but also for services like wifi
**AAA Framework**
Lenovo. https://www.lenovo.com/us/en/glossary/aaa/?orgRef=https%253A%252F%252Fwww.google.com%252F
The AAA framework in cybersecurity is Authentication, Authorization and Accounting. 
**Authenitcation** is used to verify a user or device trying to access a network
**Authorization** is used to determine the level of access or permissions granted to an authenticated user for specific network resources
**Accounting** is used to record and track user activity, this includes login and logout times, and etc

Governance is as important as technical skills because at the end of the day most cyber security roles falls under a business and knowing how to secure the business and translate technical terms that business partners. Also, creating things like playbooks, security protocols and things that requires pure knowledge almost always falls under a GRC role.

In today's world i believe Cloud aligns the most in today material because now thats is where all the big companies store data and run services. Cloud is the next biggest innovation of modern cybersecurity, this is because of its cost cutting solutions and the amount of data that can be stored. It is also available to anyone authorized across the world

#### Lab Infrastructure & Virtualization Setup
Cisco Networking Academy. (2024). Introduction to Cybersecurity: Virtualization and the CIA Triad.
A hypervisor is what is used to run a virtual machine on a computer
A virtual machine is another operating system ran on top of the host computer.

Isolation is important because virtual machine are often used as testing machines for computer attacks. This is why we need to contain VMs in order to prevent the threats from spreading to the host machine. 

This can be connected to how confidentiality works. No prying eyes from the VM can try to take advantage of its vulnerability and attack the main system.
Integrity can connect to how snapshots work in VMs. Snap shot are like a time machine in which you can revert back to any state the VM was in. Meaning that any modification that messes up the integrity of your VM can be fixed.
Availability connects to how a VM isn't stuck to one physical box. If the hardware it's running on crashes or dies, you can just move that VM to another server and fire it back up immediately. This keeps the system "available" and running so there is almost no downtime.

Reflection

Isolation is critical when testing software or malware because it prevents malicious code from "escaping" and infecting your actual computer or the rest of your network. By using virtualized environments, you can run dangerous files in a contained space where any damage is limited to just that one instance. Virtualization supports secure experimentation by letting you create "disposable" systems that can be instantly reset using snapshots, which encourages you to try things out without worrying about permanent consequences. This material on Packet Tracer and network simulation aligns most closely with the Network Security domain, as it focuses on how data moves between devices and how to configure secure pathways. This kind of hands on practice is exactly what is needed for someone working toward certifications like Network+ or Security+.