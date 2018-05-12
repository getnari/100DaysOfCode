
## Mission Statement

My background is that of obtaining a Computer Science undergraduate degree, and pausing work after a mid-career run as a general technologist with a focus on enterprise web content management systems.

#### My broad purpose in committing to the 100DaysOfCode challenge is manifold

- Get job ready again after a period off from work.
- Update my skills as the landscape is constantly changing.
- Diversify the coding paradigms I am familiar with.
- Solidify my grasp of coding paradigms I've already used in the past.
- Develop a portfolio.
- Complete several personal passion projects, which I will discuss below.
- Make open source contributions on an ongoing basis.
- Learn stuff just for the sake of learning!

#### What personal projects do I look forward to completing?

- A talk/presentation for Women Who Code Austin called "Stupid Memory Tricks," all about memory management, pointers, and the stack in C.
- Moving three websites I've built for friends off of a CMS and onto something hand rolled to be implemented on a cheaper host.
- Two viable iPhone app ideas, one of which leverages the augmented reality kit.
- Teach a class for Girl Develop It.

#### What do I plan to learn, and how?

- Source control from: Code School
- Front end web development from: FreeCodeCamp
- Front end development with module pattern from: Big Nerd Ranch's Front End Development book
- SASS from: TBD
- Node.js from: Big Nerd Ranch's Front End Development book
- React.js from: Code School
- React Native from: TBD 
- Visual Design from: Code School
- User Experience Design from: UX 101 textbook and Udemy
- Enterprise Java web development (would like to build on previous experience)

#### What milestones do I foresee?

- Finish Mission Statement
- Setup GitHub Pages Blog
- Customize GitHub Pages Blog
- Finish setting up development VM
- Finish customizing development tools and environment
- FreeCodeCamp certificates
- Finish Code School courses
- Finish Udemy UX course
- Finish reading and applying textbooks
- Gather and explore additional resources / depth areas
- Read bookmarked articles (ongoing)

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/100DaysOfCode/{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
