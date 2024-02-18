# Computational Hydraulics Group at The Oden Institute for Computational Engineering and Sciences Official Website



This website is developed from the template [Alembic](https://alembic.darn.es/). Thank you!


Live at [https://ut-chg.github.io](https://ut-chg.github.io).


# development guide

Update Website Content: commit to the main branch.


[Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

## How to add news?

1) Create a new markdown file under /_post folder, name it in the date-title.md format (e.g. 2023-01-01-firstpost.md)
2) In the markdown file, include the follow content.

```
---
title: your title
categories:
- Workshop(or any other categories)
feature_image: "https://flodismod.github.io/assets/cover_photo.png" (the image on the top of the page)
---

On the News & Outreach page, there is a list of posts. Here you put the preview text, which will be shown below the title of this post.
<!-- more -->

Maintext
<br>

{% include button.html text="Back" link="/news/" %} (this is the button to take you back to news & outreach page)
```


## How to add new group member?

1) Go to /_includes, find profile_card.html.
2) Add the following block after the last card:

```
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
    
```

To avoid error, make sure you don't put ".md" in the href of 
```<p ><a href="../ourteam/profile_NewMember">view bio</a></p>.```

3) Go to /ourteam, create a new markdown file profile_NewMember.md, and put the following information down:

```
---
feature_text: |
  ## Team

feature_image: "/assets/cover_photo.png"
---
{% include profile-short.html name="" extra="" position="" position2=""  bio="" link="/assets/team_profile/"%}

[name of the web link](the actual link)

{% include button.html text="Back" link="/groups/" %}
```


## How to add new research topic?

1) Go to /_includes, find display_research.html.
2) Add the following block after the last card following the example:

```
<div class="card">
  <a href="/project/adaptive_mesh"><img src="/assets/project/melioidosis.png" alt="Avatar" style="width:100%"></a>
    <div class="bottomWrapper">
      <a href="/project/adaptive_mesh"><h6><b>Improving the Efficiency of Wave and Surge Models via Adaptive Mesh Resolution</b></h6></a> 
    </div>
</div>
```

3) Go to /project, create a new markdown file adaptive_mesh.md. In the markdown file, put the following information down:

```
---
title: Title of your project
feature_text: |
  Research

feature_image: "/assets/cover_photo/pier.png" (save the project cover photo in the same directory and quote it here)
feature_credit: Photo by someone (leave it blank if no photographers)

---
<br />

maintext



{% include button.html text="Back" link="/research_page/" %}
```

## How to edit the navigation bar?

1) Go to _config.yml and edit section under # 9. Site navigation.
   
