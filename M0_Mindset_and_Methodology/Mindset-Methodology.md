# Module 0 - Mindset and Methodology

Before learning more about Techinques or Skill looking so cool, we should know more about **Hacking**.

## Hacking? What is this?

Most people associate terms "Hack", "Hacking" or "Hacker" with negative thoughts. But hacking isn't always bad! Some hackers do it for money or fame, while others do it for bounties, security research, or just out of pure curiosity. Everyone agrees hacking is fascinating, but to me, hacking is simply about **leveraging behavior**. 

Yes, hacking is about figuring out how things work. What happens if I try an input that no one else has used and get a strange result? It's about finding out, understanding the underlying mechanism, and seeing what we can do with it.

For example, imagine a website asks you to enter your name, and it prints `Hello <Name>` example `Hello Shurayz` inside a HTML Heading 1 tag (`<h1>`). I tried a few input and thought about it realized the web probably takes my input, creates a string `s = "Hello " + myname`, and renders it on the web page. So, what happens if i try HTML code in myname input, such as `<i>Shurayz287</i>`? 

The resulting HTML page would change from `<h1>Hello Shurayz</h1>` to `<h1>Hello <i>Shurayz287</i></h1>`. How will the browser render this?

You can try it yourself with my [index.html](./index.html) file, so just open it in any web browser! To answer the question, it will display the name "*Shrurayz287*" in italic text! 

That right there is hacking! We manipulated the system to do something the developer didn't anticipate.

## Ethical Hacking Fundamentals

This section provides the core concepts of the Ethical Hacking world. Think of it as the *language* of security professionals. As beginners, we must learn and apply these concepts so that when we join an organization or a security team, we speak the *same language*. Having a systematic understanding helps us attack and defend more effectively, making it easier to approach both hacking and cybersecurity.

### Ethical Hacking vs. Cybersecurity 

**Hacking** and **Cybersecurity** are two sides of the same coin. Hacking is the offense (Attack), while Cybersecurity is the defense. In the industry, we often refer to this dynamic as the **Red Team** (Attackers) and the **Blue Team** (Defenders). 

While the word "hacking" usually gives off a destructive vibe, **Ethical Hacking** builds a stronger defense by actively finding vulnerabilities *before* the bad guys do. We don't exploit flaws to cause damage; instead, we write detailed reports for the owners of the system, website, or server so they can patch the holes. 

To clearly understand who is who in this cyber battlefield, here are the three core types of hackers: 

- **`Black Hats`**: They use their extraordinary computer science knowledge and skills for illegal, malicious, or selfish purposes (data theft, ransomware, ...). 

- **`White Hats`**: Their ultimate purpose for hacking is defense! They always hack with permission. You might know them professionally as *Penetration Testers* (Pentesters) or *Bug Bounty Hunters*.

- **`Gray Hats`**: They operate in the gray area between offensive and defensive. They might hack a system without permission just to see if they can, but instead of exploiting it maliciously, they report the vulnerability to the vendor to help improve the product. But without **Permission**, this is illegal!

### Limitations

**White Hats** and **Black Hats** have the same process to attack the system, but answer of the core question is not the same! What i do with hacked system? 

> **`Black Hats`** steal the data, create backdoors, extort money and stalk the network. This is illegal!

> **`White Hats`** test strictly within legal obligations, contracts, and commitments with the system owners. 

In the Bug Bounty and Pentesting world, these legal obligations are defined by two main concepts:

- **Scope**: What you are allowed to hack (In-Scope) and what you must NEVER touch (Out-of-Scope). If you find a critical bug (like Remote Code Execution) on an Out-of-Scope domain, you do not get a bounty; you might get sued!

- **Rules of Engagement (RoE)**: How you are allowed to hack. For example, the rules will clearly state: No DDoS attacks to crash the server, and no phishing employees.

You know, the boundary between White and Black is very fragile. **`Just one small action outside the Scope or RoE when bug hunting instantly turn a White Hat into a Black Hat!`**

## Essential Skills

Cybersecurity and hacking are massive fields. Everyone wants to learn everything and become an extraordinary hacker overnight, but that requires immense time, patience, and effort. In reality, most hackers specialize deeply in a few specific areas (like Web or Active Directory) while maintaining a foundational understanding of the rest. 

So, what are the absolute essential skills to get started? Based on books, industry blogs, and my perspective as a Computer Science student, you cannot break a system if you don't know how it was built. Here is the core, step-by-step technical roadmap you need to master:

1. **`Programming`** Every one should start with it, you must understand how computers execute logic and how software, web app are built before you break, crack or exploit it.
2. **`Operating System`** Understanding the core of Linux and Windows (architecture, file system). The terminal where you perform you skill!
3. **`Computer Networking`** You know how internet work? How data travels between computers to intercept and manipulate it.
4. **`Scripting`** Automate your tasks, or write your own tools using Bash or Python. Writing it make us to be a hacker!
5. **`Web Application and Databases`** The best goal for Bug Bounty Hunters. Understanding Front-end, Back-end, Client-side, Server-side, how web application work? How we interact with it? Why we need to have Databases? And how it used? In web? In infrastructure?

This is not at all! There are many many many topic, skill and category in Hacking such as Cryptography, Reverse Engineering, Forensic, App Security, ... Yeah, you can learn more than what i suggest! This is a great thing! 

