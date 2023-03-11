### Hi there 👋

This is my GitHub page. I recently took it upon myself to clean it up, so it is still very much a work in progress. My background is in statistics and AI/ML and I am a long time Linux user. This is my private account, so you will not find all my projects here. For professional activities, I would like to refer you to my LinkedIn page, the link is below. 


<div id="container", text-align: justify>
  <div class="box1">
    <a href="https://www.linkedin.com/in/pietergeelen/">
      <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
    </a>
  </div>
  <div class="box2">
    <a href="https://stackoverflow.com/users/10093446/pieter-geelen">
      <img src="https://img.shields.io/badge/stackoverflow-orange?style=for-the-badge&logo=stackoverflow&logoColor=white" alt="Stack Overflow Badge"/>
    </a>
  </div>
  <div class="box3">
    <img src="https://komarev.com/ghpvc/?username=psmgeelen&style=flat-square&color=blue" alt=""/></div>
  <span class="stretch">
  </span>
</div>


div{
    width:530px; /* I changed the div size, because you a have fixed width otherwise you should use scrolling */
    border:1px red solid;
    text-align:justify;    /* You will justify to 100$ of containing div, if you want to "center" just add another div with % size and centered */

}
div span{ /* I worked with your example you may use a class */
    width:60px;
    border:1px yellow solid;
    display: inline-block; /* Inline-block */ 
    position: relative; /* relative to container div*/
}

div:before{
    content: ''; /* position for block element*/
    display: block; /* the block part for the last item*/
    width: 100%;
}

div:after {
    content: '';
    display: inline-block; /* inline-block for the first (and middle elements) */
    width: 100%;
}

<!--
**psmgeelen/psmgeelen** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
