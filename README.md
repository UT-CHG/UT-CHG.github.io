Computational Hydraulics Group at The Oden Institute for Computational Engineering and Sciences Official Website



Developed from [Alembic](https://alembic.darn.es/).


Live at [https://ut-chg.github.io](https://ut-chg.github.io).



Update Website Content: commit to the main branch.



## How to add news?

1) Create a new markdown file under /_post folder, name it in the date-title.md format (e.g. 2023-01-01-firstpost.md)
2) In the markdown file, include the follow content (news_example.txt).


## How to add new group member?

1) Go to /_includes, find profile_card.html.
2) Add the following block after the last card:

'''
<div class="card">
    <div class="box2"><img src="/assets/team_profile/new_member.png" alt="Avatar" style="width:100%"></div>
    <div>
        <h4><b>FirstName  LastName</b></h4> 
        <p></p>
        <p class="d">role, Institute</p>
        </div>

    <div class="bottomWrapper">      
        <p ><a href="../ourteam/profile_NewMember">view bio</a></p>
    </div>
</div>
    
'''

To avoid error, make sure you don't put ".md" in the href of <p ><a href="../ourteam/profile_NewMember">view bio</a></p>.

3) Go to /ourteam, create a new markdown file profile_NewMember.md, and put the following information down (profile_example.txt).


## How to add new research topic?

1) Go to /_includes, find display_research.html.
2) Add the following block after the last card following the example:

'''
<div class="card">
  <a href="/project/adaptive_mesh"><img src="/assets/project/melioidosis.png" alt="Avatar" style="width:100%"></a>
    <div class="bottomWrapper">
      <a href="/project/adaptive_mesh"><h6><b>Improving the Efficiency of Wave and Surge Models via Adaptive Mesh Resolution</b></h6></a> 
    </div>
</div>
'''

3) Go to /project, create a new markdown file adaptive_mesh.md. In the markdown file, put the following information down (project_example.txt).
   
