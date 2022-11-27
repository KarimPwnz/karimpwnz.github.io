---
layout: page
title: About
---

I am **security researcher** and **computer science student** at the [University of Southern California](https://www.usc.edu/). My experience is primarily in web-application bug bounties, having reported security issues to Google, Microsoft, Spotify, Grammarly, and more. 	

<img style="display:block;margin:2.6rem auto;" src="https://user-images.githubusercontent.com/18099289/204139083-746bdfc3-844d-458f-8ba1-224937088d2d.png" height=50px>

During the summer of 2022, I was an Associate Application Security Engineer at Bugcrowd, where I triaged security issues for customers like Dell Technologies, Pinterest, and 1Password.

I've built security tools, [contributed browser code (Firefox)](https://bugzilla.mozilla.org/user_profile?user_id=645827), written browser extensions, and worked on other development projects.

## Projects

### [sourcegraph-scripts](https://github.com/KarimPwnz/sourcegraph-scripts) (2022)

A set of **Python** scripts to identify vulnerabilities in GitHub projects using **Sourcegraph**. The scripts download code files from Sourcegraph results; subsequently, static analysis is applied to identify vulnerabilities en masse. This demonstrates a unique use-case of Sourcegraph for security research.

**Tech stack:** *Python, Bash, Semgrep, Git*

![](https://i.imgur.com/FEnvqoc.png)

### [dns-exfil](https://github.com/KarimPwnz/dns-exfil) (2021)

A **Python** tool to start a DNS server for exfilitration or ping-back detection. The tool supports hex encoding and outputs JSON, allowing easy parsing with something like jq. The project has been successfully used to detect the Log4Shell vulnerability.

**Tech stack:** *Python, DNS, Git*

![](https://github.com/KarimPwnz/dns-exfil/raw/main/misc/dns-exfil-display.png)

### [censorship-detector](https://github.com/KarimPwnz/censorship-detector) (2021)

A browser extension (in **JavaScript**) that identifies website censorship techniques. Although experimental, it can recognize DNS, HTTP, SNI filtering—all from a browser extension. I built the extension to tackle censorship of sites in Lebanon, my home country.

**Tech stack:** *JavaScript, HTML, CSS, npm, Webpack, WebExtensions API, Git*

![](https://github.com/KarimPwnz/censorship-detector/raw/main/misc/extension.png)

## Contributions & Publications

- [The Story of the Million Dollar Bounty](https://edoverflow.com/2020/houseparty-hack/) (2020)
- ["CI Knew There Would Be Bugs Here" — Exploring Continuous Integration Services as a Bug Bounty Hunter](https://edoverflow.com/2019/ci-knew-there-would-be-bugs-here/) (2019)
- [Employee’s GitHub Token Found In Travis CI Build Logs](https://hackerone.com/reports/496937) (2019)
- [Security Features of Firefox](https://blog.detectify.com/2019/10/03/karim-rahal-security-features-of-firefox/) (2019) <label>Detectify</label>
- [Stored XSS-ing Millions Of Sites Through HTML Comment Box](https://labs.detectify.com/2017/01/18/stored-xss-ing-millions-of-sites-through-html-comment-box/) (2017) <label>Detectify</label>
- [Guest blog: Karim Rahal on a Spotify playlist hack](https://blog.detectify.com/2016/01/26/guest-blog-karim-rahal-on-a-spotify-playlist-hack/) (2016) <label>Detectify</label>

## Press Appearances

- **ZDNet:** [CI build logs continue to expose company secrets](https://www.zdnet.com/article/ci-build-logs-continue-to-expose-company-secrets/) (2019)
- **TheNextWeb:** [How a popular website plugin became a serious security liability](https://thenextweb.com/news/how-a-popular-website-plugin-became-a-serious-security-liability) (2017)
- **SecurityWeek:** [Comments Widget Exposed Many Websites to Attacks](https://www.securityweek.com/comments-widget-exposed-many-websites-attacks) (2017)
- **The Register:** [Kid hackers break XSS defences, find hack hole in 2 million websites](https://www.theregister.com/2017/01/24/kid_hackers_break_xss_defences_find_hack_hole_in_2_million_websites/) (2017)
