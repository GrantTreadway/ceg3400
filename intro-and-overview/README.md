# Lecture 1 - A Clear and Present Danger

Truth needs a soldier

![truth-is-out-there](https://raw.githubusercontent.com/mkijowski/ceg3400/master/intro-and-overview/imgs/the-truth-is-out-there-x-files.jpg)

---

## Todays Objectives
* Cover changes to syllabus
* Define Cyberspace
* Take a (bogus) quiz
* Define Information Security (CIA triad)
* Define Cyber Security
* Define Risk
* Define Vulnerability
* Define Threat
* The Risk Management cycle
* Homework

---

## What is [Cyberspace](https://en.wikipedia.org/wiki/Cyberspace)?

Cyberspace is a domain characterized by the use of electronics and the electromagnetic spectrum to store, modify,
and exchange **data** via networked systems and associated physical infrastructures. In effect, cyberspace can be
thought of as the interconnection of human beings through computers and telecommunication, without regard to
physical geography.[1](http://searchsoa.techtarget.com/definition/cyberspace)

What **data** are we talking about?

Go take the quiz (Reminder, this quiz is bogus, I will be sharing all responses with the class, the only way to fail it is not take it)!

Sure did take a while to bring up the human beings in all this...

---

## What is the CIA triad [Information Security](https://en.wikipedia.org/wiki/Information_security) model?

![CIA triad](https://raw.githubusercontent.com/mkijowski/ceg3400/master/intro-and-overview/imgs/CIA-Triad-confidentiality-integrity-availability.png)

confidentiality, integrity, availabilty

**Confidentiality**: ensure only authorized access to needed data.  Prevent unauthorized access AND access to unnecessary data.

Ways to protect confidentiality: 
* encryption
* access control/file permissions
* authentication

**Integrity**: ensure the data is correct, authentic and reliable (trust).

Ways to protect integrity:
* hashing
* backups
* access/control (virtual and physical)
* data access audits
* data correcting code

**Availability**: ensure the data is available to authorized users

Ways to protect availability:
* redundancy
* physical protections
* backups
* access controls

[CEG 4750 Information Security](https://catalog.wright.edu/preview_course_nopop.php?catoid=17&coid=95990)

---

## What is Cyber Security?

Simply apply the CIA triad to Cyberspace: Ensure the confidentiality,
integrity, and availability of all data in the cyber space domain.

Easy peasy right?


---

## What is Risk
Not the board game...

![Cyber Risk](https://raw.githubusercontent.com/mkijowski/ceg3400/master/intro-and-overview/imgs/risk.jpg)

The intersection of a vulnerability, a threat, and an opportunity (or availability).

Even more specifically, a risk must have an impact, meaning it results in the 
loss of confidentiality, integrity, or availability of our data, OR the loss
of something else we care about (loss of life, income, asset, value, etc.) 

---

## What is a vulnerability?

A weakness that can be exploited by a threat actor.

---

## What is a threat 
Who are we defending from?

![mgs-alert](https://raw.githubusercontent.com/mkijowski/ceg3400/master/intro-and-overview/imgs/threat.jpeg)

Threat: a person or thing likely to cause harm

Threat Actor: a person or thing responsible for an event that impacts security.

Common Threats and Threat Actors:
* Malicious Software (software with intent to do harm)
* Software bugs (software without intent to do harm)
* Insider threats (trusted person with intent to do harm)
* ID 10 T errors (trusted person without intent to do harm)
* Outsider Threats
  * Hackers
  * Crackers
  * Script Kiddie
  * Cyber Criminals
  * Cyber Terrorists
  * Hacktivists
  * State-Sponsored attackers
  * Brokers
  * Advanced Persistent Threats

USA - 71

EU/ME - 177

APAC - 204

*As reported by FireEye, 2018*

---

## So what do we do?

### The Risk Management cycle:

1. Information gathering:
  * Identify data and assets
  * Identify threats
  * Identify vulnerabilities
  * Identify impacts

2. Evaluate Risk

3. Decide:
  * avoid
  * mitigate
  * share
  * accept

Repeat this cycle, forever...

Does anyone notice any problems or flaws with this cycle?

* 7.9 Billion people
* 21.5 billion interconnected devices
* ![cve-per-month](https://raw.githubusercontent.com/mkijowski/ceg3400/master/intro-and-overview/imgs/cves-per-year-month.png)

![so-are-lies](https://raw.githubusercontent.com/mkijowski/ceg3400/master/intro-and-overview/imgs/Truth-is-out-there-but-so-are-lies.jpg)


---

## Homework
1. [Watch](https://www.youtube.com/watch?v=2BldESGZKB8)  and read what a [hash function](https://en.wikipedia.org/wiki/Hash_function) is. (watch the video, then read the intro and overview)
2. Get access to a linux system (WSL Ubunut, bash, AWS linux).
3. Be familiar with using `md5sum` and `sha256sum` (be able to hash a file or string)
4. Read this: https://auth0.com/blog/adding-salt-to-hashing-a-better-way-to-store-passwords/#Attacking-Unsalted-Passwords



