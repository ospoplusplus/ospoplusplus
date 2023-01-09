---
title: "Empowering communities worlds apart "
date: 2021-11-08T14:50:26+06:00
draft: false
image: images/resource/St-Francis-Neighborhood-Center.png
description: "Deploying open source at St. Francis Neighborhood Center"
author: Brian Proffitt, Bryan Behrenshausen, and Ruth Suehle
studies: "Case Study"
---

## Executive summary

- Successful collaboration among three organizations—a community center, a university’s open source program office, and
a government IT department—to deploy Lutèce, a modular
open source platform designed for public support.
- Project enabled St. Francis Neighborhood Center (SFNC) in
west Baltimore, Maryland (USA), to become the world’s first
“[smart community center](https://www.stfranciscenter.org/).”
- Expertise, assistance, and sustained support from the newly
formed Open Source Program Office (OSPO) at Johns Hopkins University accelerated success of the initiative.
- Collaboration generated upstream code improvements to the [Lutèce project](https://lutece.paris.fr/lutece/).

## Background

Without the communities that unite to pursue common goals and tackle shared
challenges, open source software development could never succeed. And yet those two distinct concepts of “community” and “open source” are so firmly intertwined that we tend to forget this
important fact. A brownstone building on Linden Avenue in Baltimore, MD (USA) offers a powerful reminder of it. That’s where the St. Francis Neighborhood Center (SFNC) resides. Since
opening in 1963, the center has drawn strength from its surrounding community to become a focal point in the fight against generational poverty in West Baltimore’s Penn North and Reservoir
Hill neighborhoods. 

The fight is not an easy one. This part of the city is home to approximately 1,200 children living below the U.S. poverty line. To enhance these students’ lives, the SFNC has created after-school programs in art, health, exercise, technology, and STEM-focused areas (to name only a few). For SFNC staff, these programs demand significant time and attention. And youth-focused education is not the only service SFNC provides; it also offers job training, community cleanups, and emergency housing support. The center aims to be a safe place for neighbors to gather, learn, and share.
From its founding, the center has embraced tactics and methods that would be immediately familiar
to any open source community manager: seeking and integrating feedback from multiple stakeholders
(including community members and parent liaisons), empowering students to design and lead their own
educational programs, and establishing a board of directors that includes people who live and work in these neighborhoods. Community is at the heart of everything the SFNC does.

### Partners an ocean away

A very different organization dedicated to public
good, the City of Paris Information Technology department, sits 7,200 km and an ocean away. From
here a team of approximately 600 supports and enables the 2.2 million citizens of Paris not only to
function but to thrive. To help accomplish its mission, in 2001 the city launched Lutèce, an open source content management system (CMS) and platform that enables users to build custom websites. Combined with added functionality from modular software components, the platform serves the citizens of Paris in myriad ways. That library of components has grown since the
project’s launch, and Lutèce now incorporates more than 500 modules, enabling a degree of scalability and flexibility that is impressive for any size publicservice organization. Yet while Lutèce was open source software, it lacked a consistent and sustainable community of external contributors—until recently.

### An OSPO next door

Between these two different public-service organizations lies Johns Hopkins University, a worldrenowned private university focusing on research in many academic areas. Located just less than 3 km from SFNC, Johns Hopkins University shares not only a city with the center but also a commitment to improving the lives of Baltimore citizens. In recent years, the university has encouraged the use of open source technologies and methods amongst faculty, staff, and students. To centralize all the open source efforts growing within its halls—and to introduce a level of sustainability for open source participation—Johns Hopkins’ Digital Research and Curation Center (DRCC) launched an Open Source Program Office in 2019. Its mission is to focus on
“operational and engineering aspects of open source programs and strategic priorities such as educational experiences and partnerships with the broader [community](https://drcc.library.jhu.edu/open-source-programs-office/).” And more importantly for this story: the OSPO espouses the university’s commitment to working
alongside organizations within Baltimore.

<i> About St. Francis Neighborhood Center
Location: Baltimore, Maryland, USA
Size: 16 staff and more than 50 volunteers
Industry: Non-profit organization, community service</i>

## Challenges

Like many community and neighborhood centers, SFNC’s mission is broad, and the organization often struggles to find adequate resources for achieving its goals. Nevertheless, the center’s accomplishments have been impressive.

According to Executive Director Christi Green, SFNC currently serves about 125 children per month
in its after-school program—a program so popular that it has a three-year waiting list filled with names of children hoping to get in. In total, the center provides programs to about 500 people in a month’s time. A recent successful capital campaign phase has added new facilities to the center, which should double the number of children the center serves and enable greater impact for the center’s whole-family programs as well. But this growth introduces its own set of challenges, not least of which is increasing logistical complexity: scheduling both students and staff and
coordinating use of facilities like meeting rooms, classrooms, and the SFNC Computer Center’s resources. Lutèce is well-suited to help organizations manage such complexity. But as SFNC lacked a
dedicated development and maintenance staff, the organization had little chance of successfully adopting Lutèce for its own administrative needs.

### A special case

Elsewhere, however, Lutèce adoption was accelerating. The IT department in Paris’ City Hall noted
an uptick in usage since the project’s 2001 launch. In recent years, the organization says adoption has been even broader. Several years ago, the city of Lyon adopted—and found success with—the framework while developing new digital services. More recently, the City of Budapest adopted Lutèce and certain modules for a citizen-participation budget project the Hungarian city has launched. And according to Lutèce’s Technical Project Manager, Philippe Bareille, a network of French elder-care centers reached out to his Parisian team to implement the appointment booking modulesfor scheduling resident visits during COVID-19 lockdown and restrictive periods.
Those organizations, however, had the benefit of their respective IT staffs—so deployment was not
particularly difficult for them. And both implementations effectively consisted of the core Lutèce platform and existing modules; neither required much modification beyond look-and-feel and configuration changes.

<i>Getting Lutèce to work in an organization like SFNC would require a dedicated team of
engineers to customize the platform for the SFNC’s specific needs, host it, and support it with the kind of routine security and feature maintenance that any modern complex software installation would need.</i>

Getting Lutèce to work in an organization like SFNC would require a dedicated team of engineers
to customize the platform for the SFNC’s specific needs, host it, and support it with the kind of routine security and feature maintenance that any modern complex software installation would need. But given its own public requirements—not only with Lutèce, but also with every other project it supports on a daily basis—the City of Paris simply couldn’t provide this kind of support.

<i>About the Department of Information Technology, Paris Location: Paris, France Size:
600 staff Industry: Public organization</i>

## Solutions

Software developers, systems engineers, and project managers from the Johns Hopkins Open Source Program Office (OSPO) would ultimately be the connective fiber linking these two potential partners. OSPO developers and sysadmins could provide the level of configuration and support needed to deploy Lutèce for the Center.

This wasn’t the first time the SFNC had worked with Lutèce and Johns Hopkins. In 2018, a team
participating in the [Hophacks](https://hophacks.com/) hackathon learned of another specific need the center had: matching
homeless persons with shelters’ available beds. The offline method of addressing this need—calling
a particular homeless shelter in order to locate a space for someone in need of a bed—might yield an available spot, but in the minutes required for the person to learn of the availability and actually get to the shelter, that spot could be gone, Green explained. And this challenge is even more complex, according to DRCC Director and OSPO lead Sayeed Choudhury, when considering multiple client needs: Does a particular shelter house children? Is it women-only? Will it have power outlets available for medical devices? Can pets be sheltered there, too?

<i>The formation of the Johns Hopkins OSPO in 2019 would prove to be the
ultimate solution to all three organizations’ challenges.</i>

### Help from the hackers

A student team in the 2018 Hophack hackathon knew the city of Baltimore was unlikely to solve the
problem on its own (it’s an intimidating challenge for any U.S. municipality). But the team could help if it had just one resource from the city: a live data feed from participating shelters. The team planned and roadmapped a new module for Lutèce that could eventually tap into a data feed from Baltimore City, should it become available, and enable a live dashboard showing availability of beds suiting a much broader set of needs. The student team’s plan was a strong demonstration of Lutèce’s benefits. But while student teams are brilliant and creative, the nature of academic life
means they are also rather transitory. During their academic tenure, students’ priorities will shift as they take new classes, tackle assigned projects, and engage new opportunities. In many ways, academic life encourages that kind of experimentation and ex-posure to new experiences. But it can stymie longterm participation in open source projects—not to mention ongoing, sustainable engagements with organizations like SFNC. And eventually students graduate, taking valuable knowledge, experience, and volunteer time with them into post-matriculation
life. So Green and Choudhury independently agreed that while single-task projects like hackathons have benefits, the SFNC needed longer-term support than something like a hackathon event could provide. The formation of the Johns Hopkins OSPO in 2019 would prove to be the ultimate solution to all three organizations’ challenges. By focusing open source resources, projects,
and efforts inside Johns Hopkins, the OSPO would be able to organize teams of developers, sysadmins, and planners to complete projects like deploying a more robust Lutèce-based solution for [SFNC](https://technical.ly/civic-news/paris-lutece-open-source-platform-city-services-west-baltimore-community-center-st-francis/). Which is exactly what happened next.

<i>Open Source Program Office, Johns Hopkins University
Location: Baltimore, Maryland, USA
Size: Multiple software developers, systems administrators, and project managers
Industry: Non-profit organization, academic</i>

## Results

The collaboration has clearly benefited all three organizations. The City of Paris saw the fruits of its IT department’s efforts successfully deployed in an organization with which it might not have otherwise worked. For Lutèce founder Pierre Levy and the open source developers who have contributed to the project over decades, seeing the project successfully deployed in an environment with such unique requirements and
demands was the realization of a dream.

More practically, Bareille added, modifications the JHU team made to Lutèce were significant
enough to warrant merging back into the core Lutèce source code, where they could benefit all users of future versions. Indeed, Bareille is very happy to report that significant modifications have been merged and will appear in the upcoming Lutèce Core 7 software release. Work from SFNC
will help improve the system’s language and locale management.

<i>Seeing the project successfully deployed in an environment with
such unique requirements and demands was the realization of a dream.</i>


### Powerful proof

Johns Hopkins measures the impact of its achievement not only by its successful deployment
of Lutèce for the SFNC. The organization also sees in the work a power proof-of-concept project that demonstrates the value of focusing a major university’s resources on open source projects in a sustainable and organized way. Experience deploying Lutèce at SFNC also equips the OSPO to scale and replicate that deployment to other neighborhood and community centers around the world, which will be a huge benefit for such organizations globally.

### Complexity managed, influence magnified

From this collaboration the SFNC gains access to
a flexible, powerful system that will enable neighbors and residents to use the Center’s resources
and facilities far more efficiently, magnifying the positive impact of the Center’s programs in neighborhoods that need it—and beyond. Already, the Center is working with the Women’s Housing Coalition (WHC) in Baltimore to address the problem of emergency housing—specifically, the issue of helping families on the verge of losing [housing](https://www.womenshousing.org/). Often, Green says, heads of households might not realize they are about to lose their homes, either through
misunderstandings, miscommunications, or even denial of the circumstances. This can lead to situations such as the one facing a mother and her four kids, who lost their housing but avoided experiencing homelessness when the SFNC, the WHC, and the City of Baltimore all stepped in to provide a hotel room for the family. It was a situation where the solution was reached, but the amount of time and effort involved was far more complicated than it needed to
be. Working with the SFNC, the Coalition is applying for a Federal Housing and Urban Development
grant to create a network of up to 16 housing units as emergency homes for people when they are
needed. Lutèce will play a significant role in the logistical scheduling and management of this emergency housing network. Observers will often point to open source software’s technological advantages: increased speed of improvement, better security, or creative solution
building. These are all certainly valid. But St. Francis Neighborhood Center, its staff, and its volunteers demonstrate the most powerful aspect of open source: community. 

### Additional resources

- [Explore open source in Paris](https://opensource.paris.fr/ossparis/english.html)
- [Read the SFNC 2020 Annual Report](https://www.stfranciscenter.org/what_we_do/annual-report.html)
- [See SFNC in the news](https://www.stfranciscenter.org/what_we_do/news/sfnc-in-the-news.html)