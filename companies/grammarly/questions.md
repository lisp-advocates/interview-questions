## Introduction

Grammarly is well known for being one of the only companies to tackle the
bleeding edge NLP research with Common Lisp, as well as machine learning and
deep learning in their innovative push to deliver a digital writing tool to
more than 20 million customers.

First releasing their software in July 2009, Grammarly has had a valuation of
$1 billion as of October 2019, which made it the first Ukrainian [unicorn](https://en.wikipedia.org/wiki/Unicorn_(finance)) startup.
Grammarly is headquartered in San Francisco and has offices in Kyiv, New York
and Vancouver.

Grammarly is [using Common Lisp on
backend](https://www.grammarly.com/blog/engineering/running-lisp-in-production/)
as a foundation for its core grammar engine.

## Development

### Ecosystem

- The [2015 article](https://www.grammarly.com/blog/engineering/running-lisp-in-production/)
  states you use SBCL in production and CCL for development. Is it still true in
  2020? How difficult/easy has it been to debug multiple implementations at the
  same time?

- Have you considered switching to commercial Lisp implementations such as
  LispWorks or Allegro?

- Which Open Source libraries are important to your project? Which Open Source
  libraries has Grammarly contributed to?

- How did Grammarly choose to invest in Common Lisp specifically? Was your
  founders' previous business, My Dropbox (an application for checking students
  essays for plagiarism that has served [800 universities and about 2 mln
  students in 2007](https://escadra.com.ua/en/kak-dvoe-kievlyan-sozdali-servis-proverki-anglijskogo-pravopisaniya-stoimostyu-100-mln.html), before being acquired by Blackboard Inc), also using Common
  Lisp?

- What was your programmers' experience with Common Lisp prior to using it to
  develop such a critical part of your business?

### Workflow

- How do you organize your development process?

- Do you subscribe to any of the workflow management methods?

- How do you distribute information between the developers in your company?

- Which instant communication systems do you use within the company?

### Deployment

- What is your deployment process like? How has it evolved from 2015?

- Do you still run Erlang, Python and Go in addition to JVM languages and
JavaScript at Grammarly?

- Do you use/have you considered to use Roswell to manage your Common Lisp
  implementations?

- Do you still host your Common Lisp app on AWS?

- Which Operating System(s) do you run in production? Do you use
  containerization?

- Have you looked into hosting your own hardware park, or using specialized
  processing boards / ASICs, to run the NLP computations?

- The 2015 article "Running Common Lisp in Production" says you currently
  process more than a thousand sentences per second! Has this number changed
  since? What number of sentences do you process now?

### Documentation

- What is your approach to documenting your project, as well as specifically
  the Common Lisp part?

- Which open documentation resources do you use the most in your development?

- Which areas of the Common Lisp ecosystem could in your opinion use better
  documentation?

- What Common Lisp books or resources could you recommend to our readers?

### Difficulties

- What were the key difficulties you had to overcome on the way from checking
  students' essays for plagiarism to becoming the first Ukrainian unicorn
  company?

- What were the key difficulties related to Common Lisp? The 2015 article
  highlights some peculiar issues with GC, macro expansions, and the network
  stack you have encountered with SBCL. Have there been more curious stories
  you can share?

- Which Open Source libraries have you had limited success with? What would
  need to be changed?

- Which Open Source libraries did you find missing or lacking?

- Which areas of the ecosystem in general you believe could use more collective
  love from the Lisp community?

### Bonus questions

- Are you using or have you considered Scheme or Clojure or any other lisps?
  Why or why not? Especially since there's already JVM involvement present in
  your tech stack (as of 2015).

- What editors do your developers use? What do you recommend for new developers?

- Which Operating Systems does your team use for development?

- Does your team use Common Lisp for personal projects? What are the personal
  projects you would like to highlight?

## Developers

### Staff

- How many Common Lisp programmers does your company employ? What was the
  highest number of Common Lisp programmers to work at your company at it's
  peak?

- How many Common Lisp programmers has your company employed over it's course?
  How high is the staff turnover for the Common Lisp programmers at your
  company?

- What benefits do you offer to your Common Lisp programmers besides the
  overwhelming pleasure of using Common Lisp professionally and working on the
  bleeding edge NLP research?

### Recruiting

- How would you describe your experience with Common Lisp recruiting?

- What is your onboarding process for the new developers?

- Do you recruit developers who have experience with programming but not with
  Common Lisp? How do you get them up to speed?

- Do you offer paid or unpaid intern positions for Common Lisp programmers?

### Remote Work

- Does you company support remote positions for Common Lisp programmers?

- What were the key difficulties you've encountered with remote Common Lisp
  positions / What has prevented you from offering remote positions?

- What do you think would be the first / most efficient steps to have more
  Remote Work available in the Common Lisp ecosystem?

### Conferences

- Grammarly is [known for organizing organizing front-end developer meetings](https://escadra.com.ua/en/kak-dvoe-kievlyan-sozdali-servis-proverki-anglijskogo-pravopisaniya-stoimostyu-100-mln.html)
  in Ukraine. Has Grammarly looked into organizing more conferences, events or
  workshops since then? What about Common Lisp ones?

- Have you given or do you plan to give talks at software engineering
  conferences or events, highlighting your Common Lisp experience?

- Which lessons have you learned from organizing or taking part in conferences
  or events?

- What in your opinion are the most credible or prominent developer conferences
  within or outside the Lisp world?

### Content

- Where do you get your Common Lisp news from? Which platforms do you or your
  team use the most?

- Do you create or have you considered creating Common Lisp content?

- Do you use Common Lisp to host your content or website? What is your web stack?

### Networking

- Do you work with any other Common Lisp companies? Which Common Lisp companies
  would you like to work with?

- Which Common Lisp companies or individuals would you like to see featured in
  Lisp Interviews?

## Future

- What is your vision for Common Lisp in your company?

- What is your vision for the Common Lisp and Common Lisp ecosystem in general?
  What are the steps that you are taking to get there?

