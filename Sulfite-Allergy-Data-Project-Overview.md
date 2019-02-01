---


---

<p>Title:  Sulfite Allergy Data Project Overview<br>
Slug:  working-facebook-api<br>
Date: 2019-01-28 10:00<br>
Modified:  2019-01-28 10:00<br>
Tags: project, blog, text analytics, sulfites<br>
Author: C Withrow<br>
Summary: Overview of goals in new project to analyze discussion data from a sulfite allergy support group</p>
<h2 id="sulfite-allergies">Sulfite Allergies</h2>
<p>I have had food allergies/intolerances my whole life, without knowing it, until about 5 years ago, when I was warned by a Dr that since I have asthma, I should avoid sulfites. I had never heard of sulfites, but they can be deadly, and an estimated 1 in 20 people with asthma is allergic to them. It was difficult to find information about them at the time, but through elimination, that I am extremely sensitive to this preservative, found in many forms throughout our current food supply (it’s far more than just wine ;) ). It explained a lifetime of mysterious and worsening illness (frequent migraines, asthma, etc). But there were still so many questions, especially since this is a relatively unknown allergy and FDA only requires large amounts to be listed on products.</p>
<h3 id="enter-sulfitesnomore">Enter Sulfitesnomore</h3>
<p>Though I cleared my diet of all preservatives, frozen foods, breads, etc, I was struggling to figure out what I could eat, reacting to things I thought were safe, and still weak and miserable. Fortunately one day I stumbled on a facebook support group, Sulfitesnomore. In this group, members who’d been living and learning about sulfite allergies for decades shared their knowledge, and quickly got me headed in the right direction. The issue is generally caused by a genetic mutation and inability to metabolize sulfites, which can be greatly aided by taking certain minerals and vitamins, depending on each individual. This is important because sulfur dioxide, abundant in polluted air, is a form of sulfite, and full elimination is nearly impossible.</p>
<p>When I joined the group 5 years ago, there were only about 300 members. Now, with awareness growing among physicians, there are over 1500, with new people joining daily, many parents of toddlers who get very sick. As awareness has spread, so has misinformation, diets that make no sense and limit people unnecessarily. It’s similar to where other allergies were in the 70s/80s, except with internet frenzy added in. Managing the allergy is time consuming, everyone has lives, and we have yet to get a reliable updated website up- just a few personal blogs. So this group remains the best source of info, and is very active. I’m now the main admin, and it’s exhausting how often the same panicky questions get asked every week. We try to get members to used the search feature, but it’s not ideal. Still, I’m amazed how patiently senior members answer long, thorough messages!</p>
<h3 id="lightbulb">Lightbulb</h3>
<p>Finally, it occurred to me- why not do a chatbot? Facebook seems to make them pretty easy. But what would be the most frequently asked questions? I could guess, but why not do an actual word frequency count?<br>
And why stop there? Years ago my software engr course team started a database and app to suggest safe foods, based on surveys on safe products from members. What would be even better is to see if we could mine from the discussion data the food subjects, and user sentiment (whether safe or reacted). The possibilities are endless. And however little I find out will still be of interest to me, anyway.</p>
<p>Anecdotal evidence is often dismissed. But with increasing pollution in our water and air, and changing diets, we are all having health problems we never used to have, and a medical industry that is really designed more for handling emergencies than chronic illnesses with often subtle symptoms. Even the most skeptical have had to turn to internet forums for help and suggestions in dealing with their medical problems. It would be great to be able to look at these crowd-sourced reports more systematically.</p>
<h3 id="potential-issues">Potential Issues</h3>
<p>Of course, there may be issues- Facebook has an API, but I haven’t worked with it before, and I am not sure what all it shares. Further, the group is closed (not public), and I want to protect member privacy. All data will be aggregated anyway, and the default doesn’t show user IDs for posts and comments. However, though this would still allow a count on questions, it wouldn’t give a reliable answer count- if a veteran member has suggested X brand of coconut cream to a 100 posts, that is not the same as 100 people recommending it. For that analysis user names would be needed to eliminate duplicate sentiments.<br>
But that can be figured out in a later phase. My first goals are to get the data, and do simple frequency counts. Then build dictionaries and rules to learn as much as I can.</p>
<p>Stay tuned for posts about how it goes!</p>
<p><strong>Further Info on sulfites</strong><br>
If you are curious, here’s a few links with reliable info.<br>
<a href="https://sulfitesabc.com/">Sulfites ABC</a> Blog by the biggest authority on sulfite allergies I know<br>
<a href="http://www.learningtarget.com/nosulfites/">Learning Target</a> Written by someone with somewhat mild sensitivity, but explains a lot about how unlisted sulfites get into conventional food<br>
<a href="https://www.allergicliving.com/2010/07/02/sulphite-allergy-cooking-up-trouble/">Living Allergic Article</a> Quick overview, sulfites are also in packaging</p>

