# Reconator

---What is Reconator?---

This is a placeholder for a tool under development, for detecting adjacent hosts, vulnerabilities, and attack paths.  It will use a combination of passive techniques such as network monitoring, applying rules to fingerprint interesting devices, and active techniques that are unlikely to stand out, such as mDNS, SSPD, and DNS-SD.  While the former is likely to be more useful, the latter is easier to create so we will start there.  

---Why are we building this?---

It has been our observation that red team engagements often make a lot of noise with active scans, which are easily detected by a competent SOC with the right visibility.  However, we have also noticed that real attacks are not always so easily detected, during this important phase of discovery, which usually precedes lateral movement.  It is our goal to imagine ways that adversaries may be doing post-exploitation discovery without being noticed, replicate this as a tool that can be used in red teaming engagements, while in parallel helping to create (host) detection logic that can be applied to mitigate this risk.  As a side benefit, if the community work on host fingerprinting for this project becomes sufficiently robust, it could be forked into a new blue team project for free and open asset management.  

--- Ethical Standards / Code of Conduct ---

This project has been started to help test a scenario we are curious about, for the purpose of improving defensive posture. We can only be successful at properly defending against adversary tactics, if we have the tools and resources to replicate the approaches being used by threat actors in an effective manner. Participation in this project and/or use of these tools implies good intent to use these tools ethically to help better protect/defend, as well as an intent to follow all applicable laws and standards associated with the industry.

--- How to Contribute ---

We welcome and encourage contributions, participation, and feedback - as long as all participation is legal and ethical in nature. Please develop new scripts, contribute ideas, improve the scripts that we have created. The goal of this project is to come up with a robust testing framework that is available to red/blue/purple teams for assessment purposes, with the hope that one day we can archive this project because improvements to detection logic make this attack vector irrelevant.

1. Fork the project
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

--- Acknowledgments ---

While this project is brand new, the idea already has received lots of input and contributions, including from the following individuals. 

- [christian-taillon](https://github.com/christian-taillon)
- [adminofgits](https://github.com/adminofgits/adminofgits.github.io)
- [Duncan4264](https://github.com/Duncan4264)
- [shammahwoods](https://github.com/shammahwoods) 
- [flawdC0de](https://github.com/flawdC0de)
- [Kitsune-Sec](https://github.com/Kitsune-Sec)
