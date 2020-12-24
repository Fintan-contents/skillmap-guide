# Skillmap guide

# 1.  About this document

This document is a guide on how to implement skill maps quickly and use them effectively for development projects. 

## 1.1. Objectives

There are two main objectives for using skill maps: 

* **Visualization of risks**
* **Visualization of skills**


####  1.1.1. Visualization of risks

　Referring to a skill map makes it possible to see at a glance which skills are dependent on specific people in a development team, which enables early detection of risks to the project.

####  1.1.2. Visualization of skills

　Creating a skill map makes it possible to see the strengths and weaknesses of each member of a development team at a glance.  
　This provides some background information for smoother communication. 



# 2. How to create a skill map

This section explains how to create a skill map.

## 2.1. Selection of skills

Select the skills to put on the map.

Speak with the parties involved about the specific skills that are needed for the project and then place them along the X axis of the map. 


> **Note**:  
> There are cases in which the skills that are needed cannot be ascertained when a team is first created.  
> In these cases, place general skills such as technical elements and negotiation with outside parties on the map and keep updating the skills to improve the information that is gathered.

## 2.2.  Skill evaluations

#### 2.2.1. Mutual evaluation of skill level

  The members of the team should evaluate each other's skill level.  
  Points should be evaluated using the following three levels:  
　  
　　A ：  Can teach others how to do the task.  
　　B ： Can do the task themselves.  
　Blank： Cannot do the task (follow-up is needed).   
　  
These three-level evaluations are performed for the following reasons, although more or fewer levels can be considered if necessary. 

 - This number of levels is enough to meet the objectives of visualizing skills and risks.
 - Evaluations can be performed easily with this number of levels.

> **Note**:  
> There are cases in which team members cannot sufficiently ascertain each other's skill level when the team is first created.   
> In these cases, each member should perform a self-assessment, and the team should keep performing skill evaluations to improve the information that is gathered. 

#### 2.2.2. Selection of skills to be acquired

  Next, each team member should add a * for skills they want to acquire. (It is recommended for each team member to indicate at least one skill.)  
  Sharing plans for skill acquisition with each other encourages each development team member to work on their own professional development.

#### 2.2.3. Example of a skill map

| Name  | Java  | JavaEE | SVN   | Maven | Linux | DBMS  | Performance  | Negotiation | Design  | Document creation |
| :---: | :---: | :---:  | :---: | :---: | :---: | :---: | :---: | :---:    | :---: | :---:    |
| Yamada  | A    | B     | B    | B    | B    | B    | B    | B       | B    | B       |
| Kato  | A    | A     | B    | 　    | 　    | B    | *    | 　       | A    | 　       |
| Suzuki  | A    | A     | B    | 　    | 　    | 　    | 　    | 　       | B    | 　       |
| Nishimura  | *    | *     | B    | 　    | *    | 　    | 　    | 　       | 　    | B       |
| Tanaka  | *    | *     | B    | 　    | *    | 　    | 　    | B       | *    | 　       |
| Ito  | *    | 　     | 　    | 　    | *    | 　    | 　    | 　       | 　    | 　       |
| Inoue  | B    | B     | B    | 　    | *    | *    | 　    | 　       | A    | 　       |
| Saito  | A    | 　     | B    | 　    | 　    | A    | 　    | 　       | 　    | 　       |
| Yamamoto  | 　    | 　     | B    | 　    | B    | 　    | *    | 　       | 　    | B       |
| Mizutani  | 　    | 　     | 　    | 　    | 　    | 　    | 　    | 　       | A    | 　       |

| Symbol | Meaning|
| :--- | :---|
| A   | Can teach others how to do the task.|
| B   | Can do the task them-selves.|
| Blank | Cannot do the task (follow-up is needed).|
| *   | Wants to acquire this skill. |


# 3. How to use skill maps 

This section explains where and how to use skill maps.

## 3.1. Allocation of pair work

The following types of pair work are frequently used to increase team member's technical skills and prevent situations where only one person knows how to do a particular task.


* **Pair programming**
* **Pair investigations**

The information obtained from skill maps, such as each team member's technical skill level and whether they have knowledge about each business, can be used to pair team members in a way that is best suited to the progress of the work and how the team members are improving their skills.

## 3.2. Allocation of workshop leaders

When holding team workshops so that team members can improve their technical skills and acquire business knowledge, the * and A symbols on skill maps (indicating who wants to acquire each skill and who is able to teach others, respectively) are useful when selecting leaders.


# 4. How to update skill maps

This section explains when and how to update skill maps.

## 4.1. When to update skill maps

Skill maps can basically be updated at any time, but it is recommended to update them every two weeks to one month (or at the end of each sprint during scrum development).

## 4.2. Updating skills

As a project proceeds, you may find that another skill that is not written in the skill map is essential to your project.

Skills like this need to be added to the skill map, as the objectives of a skill map cannot be fulfilled if the list of skills is incomplete.

However, adding skills indiscriminately will make the map too complicated, so use the following voting method to determine whether each skill is essential. 

 * **The team members vote on whether to include each skill**
 * **Skills that receive votes from at least 1/3 of the team members are included**

> **Note**:  
> This voting system makes it possible to reflect the whole team's opinion when identifying skills. 


## 4.3. Re-evaluating skills

If the original skill evaluation results are kept as they are without taking into account the following point, information that is no longer correct may be used. 

* **Improvement in skill level**
* **Misevaluation**

Skills need to be re-evaluated to keep the information up to date.   
Recommended methods include performance interviews by the project leader. 

> **Note**:  
> Interviews are not only useful for updating skill maps, but also for regular awareness of leaders and members. 


## 5. Licensing

This document is provided under the<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"> international Creative Commons Attribution-ShareAlike 4.0 license</a>.
<br />
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
  <img alt="Creative Commons license" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
</a>
