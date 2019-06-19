---
title: "Starting OSCP From Scratch"
date: 2019-06-18T15:53:04-06:00
draft: false
---


<em><strong>Read Time</strong>: 16 mins</em>
**By:** Clutchisback1

I hate reading boring articles so I'm not going to waste any of your time by writing one. Besides, you're probably an PWK student with lab time ticking away each second as you get closer to your exam date; The very exam date that will determine whether or not you've become a man/woman yet in the information security industry. Right now, you're still a little boy/girl with absolutely nothing going for yourself. That's how I felt most of the time as I spent countless hours "skateboarding" through the internet trying to find some reverse PHP shell capable of running on windows host:
<p style="text-align: center;"><strong><em>It actually exists folks</em>:</strong>
(<a href="https://github.com/Dhayalanb/windows-php-reverse-shell/blob/master/Reverse%20Shell.php" target="_blank" rel="noopener">Windows PHP Reverse Shell</a>)</p>
The feeling of insufficiency coupled with the euphoria that I felt after gaining root privileges, or learning a new technique motivated me. I was like **Neo** spending hours in simulation learning Jiu Jitsu (*which was really Karate but don't get me started on that!*).

## TLDR'ers Start Here ➡️➡️

But you already know all of that so let's get right into it:

<strong>Do these:</strong>
If you are just starting PWK, you've probably already been told to go and do the <a href="https://www.abatchy.com/2017/02/oscp-like-vulnhub-vms.html" target="_blank" rel="noopener">OSCP like Vms</a>:

You've probably even been told to go and watch some of <a href="https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA/videos" target="_blank" rel="noopener">Ippsec's videos</a>.

No one probably mentioned that you could find <a href="https://github.com/abatchy17/WindowsExploits" target="_blank" rel="noopener">Pre Compiled Windows Exploits</a> out there in the wild which will save you some headache during your time in the labs.

<strong>Certainly do these</strong>:
And if no one has told you about <a href="https://exploit-exercises.com/download/">Nebula</a> for learning <span style="text-decoration: underline;">Linux privilege escalation</span> techniques they have done you a disservice!

For note taking, I used a <strong>beautiful</strong> program called <a href="https://atom.io/" target="_blank" rel="noopener">Atom.</a> Learn <strong>MARKDOWN</strong>! Markdown is sort of like HTML and is super easy to use. After launching Atom and creating your folder for note taking make a "<strong>.md</strong>" file and start from there! It can recognize code and everything!

If you want buffer overflow experience and you don't have lab access yet, I recommend doing <a href="https://www.vulnhub.com/entry/brainpan-1,51/" target="_blank" rel="noopener">Brainpan</a> on Vulnhub.
<strong>Spoiler</strong>: It has both a <em>Windows</em> and a <em>Linux</em> buffer overflow for you to pwn!

Now that you have a good starting point, I want to cover some of the unwritten rules along with some additional tips that will help you during your time in the labs and in your pentesting career. Some of these tips will save you from a lot of embarrassment and frustration in your pursuit of the OSCP certification. I want to help you by shining light on how your thinking needs to and will change during your time in the labs.
<h2 style="text-align: center;">Tips & Unwritten Rules</h2>
<div style="background-color: #e0ffe0; padding: 20px; margin-top: 0;">

1. <strong>Google</strong>,<strong> Google, Google</strong> ...need I say more?
* <b>Thaw shall not ask another pentester any questions prior to googling the subject for at least 5 minutes on the subject.</b>

2. <strong>Offsec admins are not as mean as you think they are.</strong>
* Before I used the <a href="https://support.offensive-security.com/chat.php">Offsec Support Chat</a> for the first time, I had already accepted that they were going tell me to <b>try harder</b>, but not once has any Offsec admin ever uttered those words to me. <strong>They are very understanding and super helpful</strong><b>.</b>

3. <strong>Read the write-ups</strong>.
* You should be watching yourself and making sure this doesn't become your "go to" on every single box you attempt to root, however, you are only hurting yourself when you abandon a machine without ever gaining the knowledge you are missing.

4. <strong>You are not a failure if you get stuck and look at the write-up for a box</strong>.
* This is something I struggled with for a long time. I <strong>ALWAYS</strong> felt guilty resorting to someone's write-up after exhausting all of my knowledge on a target box but once you do read the write up you will likely remember that technique for the rest of your career!
* <strong>Pro tip:</strong> Peek: scroll down to where you are stuck and only view enough to get you moving again!

5. <strong>DO NOT USE METASPLOIT</strong>:
* Using Metasploit will severely hinder your ability to pass the exam in my honest opinion. You can only use it on one machine during the exam and it is generally only worthwhile on windows machines. I mean, imagine getting to the exam and having zero manual windows privilege escalation skills because you've been using Metasploit for every box in the lab. <b>Yikes!</b> <strong>Avoid it as much as possible</strong><b>.</b>

6. <strong>Make Friends</strong>
* Building relationships is one of the best things you can do while in the labs. The more connected you are within the community the better. Offsec also provides an <a href="https://www.offensive-security.com/offsec-irc-guide/">IRC Channel</a> where you can communicate with other students and admins. I strongly suggest jumping in here before your lab time and asking your questions here <strong>Keeping rule #1 in mind.</strong>

7. <strong>Get a mentor</strong>
* Find someone who already passed <strong>OSCP</strong> or OSCE who can help do exactly what this article is doing in real time. Often times we read articles like this and forget that there is a real life person that wrote it and may be readily available in some <a href="https://chat.netsecfocus.com/nsf/channels/general">Hackthebox forum</a> somewhere. Find someone to "<strong>show you de wey!</strong>"

8. <strong>Stay up Until 3AM</strong>
* My bedtime is <strong>3am</strong> just about every night. It's gotten to the point where if I go to bed before then I will be laying there with my eyes open staring at the ceiling. Learn to optimize your available hours to pour into the labs and try not to get divorced because all you seem to care about is buffer overflows and rooting pain & sufferance! Make sure you communicate your schedule with your family and don't slack off doing your responsibilities around the home!!!

</div>
 

## Closing thoughts

Relax! You're going to do well! Check out some of my <a href="https://github.com/Clutchisback1?tab=stars" target="_blank" rel="noopener">Github stars</a> to find some really good enumeration scripts and other toys I've picked up along my journey to OSCP. If you're not familiar with Github before starting in your labs you will become familiar with it soon enough!

I leave you with this:
<blockquote>Every machine you face in the labs and in life is a mirror reflecting your pentesting skill and competency.</blockquote>
Every box you gain is a step upward in your ascension towards the glorious OSCP certification! Keep struggling! Keep learning! Keep hacking; and <strong>Stop sleeping</strong>!
