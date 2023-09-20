---
description: 'C^3: Challenge Everything'
cover: >-
  https://images.unsplash.com/photo-1550751827-4bd374c3f58b?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHwyfHxjeWJlcnNlY3VyaXR5fGVufDB8fHx8MTY5NTA4ODExNXww&ixlib=rb-4.0.3&q=85
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Canton Cybersecurity Club Docs

## Monday CTF Training Minutes &#x20;

<details>

<summary>9/18/2023</summary>

Today we embarked on our journey to develop a proficient Capture the Flag (CTF) team. We've unveiled the driving force behind choosing cloud-based attack/defense boxes.  Access credentials were distributed to members in attendance. Our team encompasses a diverse array of skill sets, reflecting various backgrounds, interests, and career aspirations.  As a result, we've taken the initiative to establish this dedicated hub where members can access training resources, meeting summaries, and weekly goals.

### Week One Tasks

* [ ] Connect on Discord to request default access credentials for the C3 attack-box.
* [ ] Familiarize yourself with a command-line interface (CLI)-based text editor such as vim or nano.

### Pick a Memorable Username

A unique and distinctive username helps you stand out. Make it easier for others to recognize and remember you. Your C3 admin will ask you for a preferred username when you request to join.&#x20;

### Updating Password

Once logged into your assigned profile you will be prompted to change your password. This is a cybersecurity club, please make sure your password is well structured. You do not want to have your password discovered during our password cracking module.&#x20;

<pre class="language-bash" data-overflow="wrap" data-line-numbers data-full-width="true"><code class="lang-bash"><strong># The passwd command can be used to change your password at anytime. 
</strong>passwd 

# C3 Admins be sure to force password change on next login for new profiles.
passwd --expire &#x3C;username>
</code></pre>

### Nano Editor

Nano is a user-friendly text editor commonly used in Unix-based systems. It operates in the terminal, making it lightweight and ideal for remote administration.

```bash
# To install nano use the following command
apt install nano

# To open a file in nano use the following command
nano pathToFile
```

#### Useful Resources

HackerSploit Nano Editor Fundamentals (YouTube): [https://www.youtube.com/watch?v=gyKiDczLIZ4](https://www.youtube.com/watch?v=gyKiDczLIZ4)

Nano Cheatsheet: [https://www.nano-editor.org/dist/latest/cheatsheet.html](https://www.nano-editor.org/dist/latest/cheatsheet.html)

### Vim Editor

Vim is a powerful and highly customizable text editor commonly used in Unix-based systems. It has a steep learning curve but offers exceptional efficiency once mastered. Vim's unique modal editing system, extensive keyboard shortcuts, and plugins can greatly enhance productivity when working with code, configurations, and text-based tasks in a secure environment.

```bash
# To install vim use the following command 
apt install vim

# To open a file in vim use the following command 
vim pathToFile
```

#### Useful Resources

ThePrimeagen Vim As Your Editor (YouTube): [https://youtube.com/playlist?list=PLm323Lc7iSW\_wuxqmKx\_xxNtJC\_hJbQ7R\&si=clvmicQuYpoABVs\_](https://youtube.com/playlist?list=PLm323Lc7iSW\_wuxqmKx\_xxNtJC\_hJbQ7R\&si=clvmicQuYpoABVs\_)

Vim Cheatsheet: [https://devhints.io/vim](https://devhints.io/vim)

</details>
