<head-bottom>
  <link rel="stylesheet" href="{{baseUrl}}/css/textbook.css">
</head-bottom>

<header sticky>
<navbar placement="top" type="dark">
<a slot="brand" href="https://se-education.org" title="SE-EDU" class="navbar-brand"><md>:fas-chevron-circle-left: ****SE-EDU****</md></a>
  <li><a href="{{baseUrl}}/index.html" class="nav-link"><md>**Home**</md></a></li>
  <li><a href="{{baseUrl}}/about/acknowledgements.html" class="nav-link"><md>**About**</md></a></li>
  <li><a href="https://github.com/se-edu/se-book" class="nav-link"><md>:fab-github:</md></a></li>
  <li slot="right" class="nav-link">
    <form class="navbar-form">
      <searchbar :data="searchData" placeholder="Search" :on-hit="searchCallback" menu-align-right ></searchbar>
    </form>
  </li>
</navbar>
</header>

<div id="flex-body">
<nav id="site-nav" class="fixed-header-padding">
<div class="nav-component slim-scroll">
<site-nav>
* **About this book**
  * [About]({{baseUrl}}/about/acknowledgements.html)
* **Project management**
  * [Revision control (using Git & GitHub)]({{baseUrl}}/gitAndGithub/trail/tours.html)
</site-nav>
</div>
</nav>
<div id="content-wrapper" class="fixed-header-padding">

# <span class="text-dark"><small>****Git-Mastery: Lessons****</small></span>
  {{ content }}
</div>
<nav id="page-nav" class="fixed-header-padding">
  <div class="nav-component slim-scroll">
  <page-nav />
  </div>
</nav>
</div>

<footer>
  <div class="text-center">
    <small>[<md>**Powered by**</md> <img src="https://markbind.org/favicon.ico" width="30"> {{MarkBind}}, generated on {{timestamp}}]</small>
  </div>
</footer>
