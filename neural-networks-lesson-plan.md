---
description: Neural Networks Lesson Plan
---

# Neural Networks Lesson Plan

{% tabs %}
{% tab title="First Tab" %}
Building blocks:

```
<i class="fa fa-pencil" aria-hidden="true"></i> **Vocabulary:** 
<i class="fa fa-refresh" aria-hidden="true"></i> **Circulate:** 
<i class="fa fa-file-text-o" aria-hidden="true"></i> **Distribute:** 
<i class="fa fa-check-square-o" aria-hidden="true"></i> **Do This:** 
<i class="fa fa-lightbulb-o" aria-hidden="true"></i> **Discussion Goal:** 
<i class="fa fa-comments" aria-hidden="true"></i> **Discuss:** 
<i class="fa fa-list-alt" aria-hidden="true"></i> **Display:** 
<i class="fa fa-comments" aria-hidden="true"></i> **Prompt:** 
<i class="fa fa-desktop" aria-hidden="true"></i> **Model:** 
<i class="fa fa-video-camera" aria-hidden="true"></i> **Video:** 
```
{% endtab %}

{% tab title="Slides" %}
{% embed url="https://docs.google.com/presentation/d/1akZ9vcjLUGn-EMa8dfaV3eE0qYr5wZ3D9ihQIcnWlm4/edit" %}
{% endtab %}

{% tab title="Resource" %}
{% embed url="https://docs.google.com/document/d/1z7ZO-9zKlmn3brqH7euWVMSOuzVTQOdWDgkGGukRkvc/preview" %}
{% endtab %}

{% tab title="Activity Guide" %}
{% embed url="https://docs.google.com/document/d/1meWWLw9LEkHBZkbkPP40XdnkeLO2x2EPKd8W9AslH-0/edit" %}
{% endtab %}
{% endtabs %}

## Warm Up (5 mins)

**Prompt:** What's an example of an experience that recommends things to you?

**Discussion Goal:** Encourage students to think of things that make recommendations, especially different apps or websites. For example, they may be recommended videos from Youtube or new songs on a music app. Some apps may ask you to pick preferences before using them to help figure out your preferences. Some websites give recommendations at the end of an experience, like a takeout menu or online grocery store recommending new items before checking out. Try to crowdsource a variety of examples before continuing to the next prompt

**Prompt:** Do these recommendations tend to be accurate? Or do they feel random?

**Discussion Goal:** Responses here will vary, and there's no expected answer. Instead, focus on the tension between getting recommendations and having them be accurate and how not every recommendation may feel like it matches each student's interests and personality.

> We get recommended things all the time, but how do these programs know what to recommend? How do they get better? Today we're going to look at one way computers create recommendations using something called neural networks.

## Activity (35 minutes)

**Distribute:** Pass out the WeTube Content Creators resource

**Display:** Display the slide with information about WeTube, which is also on the top of the handout.

**Model:** Show students the widget and demonstrate how to select a person and then view the video recommendations.

_Teaching Tip -_ **Real Or Fake?** Students may have lots of questions about this business model and why it's a good idea to only go by recommendations. These may be valid questions if this were a real business, but it's not - ensure students that this is just an excuse to focus on the role of recommendations in our world. However, it is true that the underlying concepts in this business and how recommendations work are similar to real-world recommendation systems, even if the company is fake.

_Content Corner -_ **Spotify Recommendations:** Spotify is one of many companies that uses a similar interface when users first use the app - it asks users to pick 4-5 different artists, and then curates songs based on those preferences.&#x20;

**Code Studio:** Send students to the first level in Code Studio. As they work, have them consider the following prompt

**Prompt:** Which content creator resonates with you the most and are most excited to follow? Which one resonates with you the least?

_\[Beta: WeTube Video Recommendations (Widget) level goes here]_

**Circulate:** Walk around as students experiment with the app. Make sure they understand the interface - that after choosing a content creator, they see a list of video recommendations they can explore. Encourage students to explore different content creators and see what videos are recommended. Students should notice that the videos seem to match the personalities of each person with some variation. Once most students have looked at a few content creators, regroup the class.

**Regroup:** Have students regroup to discuss the following prompt

**Prompt:** Ask the following questions in quick succession and having students respond non-verbally (for example, by raising their hands). The goal is to quickly move through these questions to motivate the next section of the lesson.

* Were there any videos that showed up for your person that you didn't think were super interesting or disagreed with?
* Were there any videos that showed up for another person that you wish had shown up with your favorite person?

> It’s super unlikely that just subscribing to 1 person will give you the ideal recommendations - there may be some things here that you actually don’t like, and you’d rather do something that a different user recommended instead. There’s gotta be a way to combine these different perspectives to fine-tune the recommendations that we get. Let’s look at how computer science and artificial intelligence can help with that!

**Video:** Show the Neural Network video

{% embed url="https://youtu.be/JrXazCEACVo" %}

**Display:** Show the "WeTube Version 2.0" slide, which describes the updates to the widget. Click through the next slides to explain the differences in the widget.

| Slide                                | Say                                                                                                                                                                                          |
| ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](<.gitbook/assets/image (8).png>) | **Display and Say:** You can now combine recommendations from each person.                                                                                                                   |
| ![](<.gitbook/assets/image (5).png>) | **Display and Say:** You can use the slider to adjust how much this person will influence your recommendations. Just like in the video, we're adding more **weight** to their recommendation |
| ![](<.gitbook/assets/image (2).png>) | **Display and Say:** You can click on someone else and combine their recommendations. The thicker the line, the more they influence the recommendations.                                     |
| ![](.gitbook/assets/image.png)       | **Display and Say:** Here are some of the recommendations we get with Sofia and Joseph. Both of their preferences are reflected here.                                                        |
| ![](<.gitbook/assets/image (9).png>) | **Display and Say:** You can also click the Select New Weights button to go back and change your preferences. For example, we could decide to add Alex to our recommendation model.          |
| ![](<.gitbook/assets/image (7).png>) | **Display and Say:** When we do that, some new videos appear in our feed that were influenced by Alex's preferences.                                                                         |

**Do This:** Use the widget to create a new set of recommendations to match your interests. Fine tune your weights until the recommendations match your interests. _\[Thomas - I added a comment here for you asking you to make a half-sheet activity guide for students to record their models]_

_Teaching Tip_ - **How Is It Learning?** This widget is similar to the example shown in the video and, behind the scenes, each person has given a rating to the different "videos" that get recommended. However, there is a key difference: in the video, the network customizes the weights by "learning" from how users rate the videos that are recommended to them, but in this widget users can manually adjust the weights to customize the network themselves. In this sense, the widget isn't really "learning" in the same way the video learns. However, it does create an equivalent type of recommendation system, and is similar to other recommendation systems that let users customize their interests themselves.&#x20;

**Circulate:** Monitor students as they complete this task. Students should be testing different combinations of weights and recommendations. Encourage students to share observations with their neighbors and really play with the combinations. Some probing questions could be:

* Are there any videos that appear for certain people?
* If you pick a particular video, is there a way to get it to the "front page" of your recommendations in your top 3?
* Are there videos that never seem to make it to the top 3?

As students begin to settle on combinations that they like, regroup the class

**Do This:** Jenna is a student who _loves_ Boba Tea. There's a video called "Boba Tea Hacks: Unique flavor combinations". She's trying to find a combination that gets this video to the Top 3 videos. Can you help her?

**Circulate:** Give students a few minutes to experiment here, but transparently: this video is designed to always be rated low by the current selection of content creators and never appear in the Top 3. This is intentional and designed to motivate the final part of the activity.

> It seemed like it was nearly impossible for Jenna to see her interest represented in her Top 3.  Thinking about how Jenna must feel, it can be pretty disappointing to not be able to see your own interests represented in an app like this.

**Prompt:** Have there been times where your interests or perspectives haven't been represented in an app? Why do you think that is?

Have students share with their neighbors

**Discussion Goal:** Students may have a wide variety of experiences here. Some may be comical or inconsequential, like not having their favorite type of food recommended to them no matter how hard they try. Others may be more influential and consequential, like never having music or books or movies reflective of their identities or culture recommended back to them. Focus the discussion on why this might be, emphasizing answers that focus on the diversity of the data used for the recommendation algorithm. When this comes up, feel free to transition to the next part of the activity.

> Recommendation systems are only as good as the data they have to work with. In this example, none of our content creators liked the Boba Tea video enough to make it rise to the top, even though people like Jenna clearly want to watch it. Sometimes this causes people to leave the app entirely, but there's also another solution: adding more perspectives to the data!

**Display:** Show the slide with the next set of directions - imagining your own content creator

* "You are now in charge of imagining a new content creator that WeTube will add to their recommendation system. This person could be based on an existing person (even yourself!), or could be totally imaginary. The key thing is that this person should represent new interests and perspectives not represented by the current group of people."

**Do This:** Design your own content creator on the activity guide

## Wrap Up (5 mins)

**Prompt:** Why is it important to have a diverse set of data when creating a recommendation system?





