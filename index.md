<frontmatter>
title: "Git-Mastery: Home"
</frontmatter>
{% from 'common/macros.njk' import thumbnail with context %}

<div class="website-content">

<header>
<div class="jumbotron jumbotron-fluid text-center" style="padding-top: inherit; padding-bottom: inherit">
  <div class="container">
  <h1 class="display-3 text-success">Git-Mastery</h1>
  <div class="lead">

Learn, practice, and receive feedback on your journey to Git mastery.<br>
A free resource **for students and teachers**.<br>
  </div>
  <hr>
  </div>
</div>
</header>


{% macro heading(icon, text) %}<h4>{{ thumbnail(icon) }} <span class="lead font-weight-bold text-green">{{ text }}</span></h4>{% endmacro %}


{{ heading(":fas-route:", "Outcome-driven lesson paths") }}
<div class="indented-level3">

Our Git lessons are divided into [tours](lessons/), each teaching a specific usage of Git. So, instead of simply learning different Git commands, you learn how to use Git to achieve specific outcomes %%e.g., how to keep track of the history of a folder, while keeping a back of it on the cloud.%%
</div>

{{ heading(":fas-dumbbell:", "Authentic exercises to practice Git") }}
<div class="indented-level3">

We provide a hands-on practicals to practice Git concepts as you learn them, and exercises that simulate authentic Git usage to test your knowledge. Our companion app can set up elaborate Git usage scenarios so that you can go straight to practicing the concept at hand, without needing the setup the scaffolding yourself.
</div>


{{ heading(":fas-spell-check:", "Automated feedback") }}
<div class="indented-level3">

Students will not need to wonder if they did the exercise correctly, or where they went wrong. The Git-Mastery companion app can give students feedback on the Git exercises they do, and verify that the result is correct.
</div>

{{ heading(":fas-list-check:", "Progress tracking/monitoring") }}
<div class="indented-level3">

Our companion app keeps track of the student's progress through the exercises. The student can even make their progress visible online.<br>
Instructors can keep track of their students' progress using a dashboard.
</div>


{{ heading(":fas-hand-holding-heart:", "Free forever. No limits.") }}
<div class="indented-level3">

Git-Mastery is entirely free. There is no account signup. There is no limits on usage.<br>
Students can use it on their own, or as directed by their instructors.<br>
Instructors can use it for their classes. No limits on class count/size.
</div>

</div>
