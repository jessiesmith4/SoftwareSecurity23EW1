# SoftwareSecurity23EW1
CS 305: Software Security at SNHU during term 23EW1
Jessie Smith

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a consulting company that provides individual financial plans for their customers through their applications, which includes savings, retirement, investments, and insurance. Artemis Financial uses a public web interface and wishes to modernize their application by protecting their clients data through encryption of the data. They also wanted to use file verification through a checksum to ensure secure communicaiton.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I think I did very well at determining which of the vulnerabilities were false positives, and while determining which configurations, ectendsions, etc. just needed to be updated to avoid any security leaks. Coding securely ensures the security of the software, it helps avoid any attacks on the software, leaks of data, etc. Protecting the data of clients and customers is one of the top priorities when it comes to developing softare, it ensures that the software will in fact be used, and it is also beneficial to a company's overall wellbeing because they will not lose customers due to data leaks, attacks, etc. I personally would not want to feel responsible if my software caused customers data to be intercepted by those with malicious intent. 

What part of the vulnerability assessment was challenging or helpful to you?

Determining which of the vulnerable dependencies were actually false positives was both challenging and helpful. It helped me determine which of the vulnerabilities actually needed to be paid attention to, and which of the vulnerabilities were not necessary. There were a lot of vulnerabilities in the first dependency check I ran, and it took a lot of reading and researching to determine which ones could be suppressed. The most challenging part was definitely the time it took, and reading through each of the reports on the dependency report.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by adding the hash function, to hash the data, and by refactoring the code to convert HTTP to the HTTPS protocol, which provides a more secure connection. In the future I will definitely use the dependency report to assess vulnerabilities, and I would also use them regularly to continually assess the results provided. Continuing to asses vulnerabilities and release patches on the software will help ensure that the software stays secure even after release.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

Ensuring that the code in fact converted from HTTP to HTTPS protocol helped me make sure that the code was functional and secure, and after refactoring the code, double checking the counts and reports on the dependency check helped me check if there were any new vulnerabilities. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I found this website that gives examples of hashing techniques in Java, and includes dependencies that might be helpful. It helped me used MessageDigest and create a hashing function for my program. Research was definitely the tool that helped me the most during this course and will continue to help me in my future assignments and tasks.
Here's the website if you'd like to check it out: https://www.baeldung.com/sha-256-hashing-java

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would include the code base that was provided and specify which parts I refactored, the hashing technique, refactoring from HTTP to HTTPS protocol, the suppresion file, etc. I will also include the projects from this course, the reports I filled out on the projects, which show my knowledge on the code, dependency reports, etc. This will help convey my knowledge on the topic to employers.
