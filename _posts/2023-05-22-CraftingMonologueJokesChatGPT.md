---
layout: post
title: Prompt to GPT-3 - Step-by-Step Thinking Instructions for Humor Generation
date: 2023-05-22 12:41:00-0000
description: In this blog, we'll explore how to use ChatGPT, a large language model by OpenAI, to write monologue jokes based on a required pattern.
categories: project chatGPT
giscus_comments: true
related_posts: false
thumbnail: assets/img/blog-joke/mic-thumbnail.jpg
toc:
  sidebar: left
---

<div class="row mt-3 text-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/blog-joke/mic.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

[//]: # (<div class="caption">)

[//]: # (    Undergraduate Students Present Their Research - RPI Undergraduate Research Fair 2023)

[//]: # (</div>)
Artificial intelligence has made significant progress in natural language processing, with models like 
<a href="https://openai.com/blog/gpt-3-apps">GPT-3</a> demonstrating impressive capabilities. 
However, these models still have limitations when it comes to complex tasks that require an understanding 
of the user, such as mastering human comedy writing strategies. 

In this blog, we'll explore explores humor generation using GPT-3 by modeling human comedy writing theory and leveraging step-by-step thinking instructions. We will break down the joke creation process into sections and discuss how this approach can help ChatGPT perform more advanced tasks.

## 1. Topic Line Creation
The first step in our methodology focuses on developing the topic sentence, which forms the basis for the joke-generation process. To guide GPT-3 effectively, we employ a specific thinking instruction that sets an environment for the model, outlines the task of generating monologue joke topics based on actual news items, and provides examples to enhance the model's understanding further. When given a news article, GPT-3 uses the information supplied by the instruction of this step to construct a single, concise statement that captures the essence. 

The instruction we used is as follows. It defines what a topic sentence is with examples:

```
We will generate Monologue joke topics for a late-night TV show 
by crafting succinct sentences based on actual news items. 

A Monologue joke comprises three parts, and our objective is to 
produce the first part - the topic. 

The topic should be founded on a real news event that grabs 
people's attention and enables amusing commentary. It need not 
be intentionally funny but must be factually accurate. 

For instance, 

`Carl's Jr. is selling a foot-long burger`

or 

`Bernie Madoff's underpants were sold at an auction`

are suitable topics. During our conversation, I will provide 
a news article, and you will create a single sentence that 
fulfills these criteria. If you believe the news article is 
inappropriate for Monologue jokes, please inform me.
```

We thus provides GPT-3 with a supportive environment by using our cognitively informed prompts, making it easier to understand the task and the expectations. The goal is to produce the first part of a monologue joke: an attention-grabbing, factually accurate, and amenable to humorous commentary topic.

Using this method, we create a strong and precise topic sentence that is the basis for later stages, ultimately producing a polished and amusing monologue joke.

During our conversation with ChatGPT, we will provide a news article and ask the model to create a single sentence that meets these criteria.

## 2. News Article

The news article will be provided by the user. See the appendix in the blog for examples.
<div class="row mt-3 text-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/blog-joke/news.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
## 3. Punchline Development: Identify Handles and Associations

To create the punchline, we need to:

1. Determine two interesting words or phrases (handles) in the topic, such as people, places, things, or actions.
2. Brainstorm a list of associations for each handle, and then create two separate lists of associations related to each handle.

Example:

```
Topic: "YouTube experiments with a new "1080p Premium" option, offering 
        higher-quality video for Premium subscribers."

Handles: "1080p Premium" and "higher-quality video“

Associations for "1080p Premium": "Premium subscribers", 
                                  "YouTube revenue", 
                                  "Exclusive content", 
                                  "Higher price", 
                                  "Upselling", 
                                  "Better experience". 

Associations for "higher-quality video": "HD resolution", 
                                         "Better image quality", 
                                         "More pixels", 
                                         "Higher bitrate", 
                                         "Sharper image", 
                                         "More data", 
                                         "Cinematic experience".
```

We'll ask ChatGPT to identify handles and associations for the provided topic, using the example format.

## 4. Punchline Development: Combine Associations

Next, we'll pair an association from one list with an association from the other list to create the punchline. It's important to evoke a negative emotion towards the first major entity in the topic for the monologue joke to be humorous.

Example:

```
We can connect "Upselling" and "Sharper image" from the associations 
list to create the punchline: "Upselling their way to a sharper 
disappointment.“
```

We'll ask ChatGPT to provide a punchline based on the association lists, using the example format.

## 5. Connect to the Topic Using an Angle and Finish Developing the Joke

Finally, we'll craft an angle to transition the audience from the topic to the punchline.

Example:

```
YouTube experiments with a new "1080p Premium" option, offering higher-
quality video for Premium subscribers. Now, viewers can pay more to 
witness their favorite cat videos in stunning clarity – upselling their 
way to a sharper disappointment.
```
We'll ask ChatGPT to continue building the monologue joke using the provided topic, handles, associations, and punchline, following the example format:

```
Topic: "YouTube experiments with a new "1080p Premium" option, offering 
       higher-quality video for Premium subscribers.“

Handles: "1080p Premium" and "higher-quality video“

Associations for "1080p Premium": "Premium subscribers", 
                                  "YouTube revenue", 
                                  "Exclusive content", 
                                  "Higher price", 
                                  "Upselling", 
                                  "Better experience". 

Associations for "higher-quality video": "HD resolution", 
                                         "Better image quality", 
                                         "More pixels", 
                                         "Higher bitrate", 
                                         "Sharper image", 
                                         "More data", 
                                         "Cinematic experience".

We can connect "Upselling" and "Sharper image" from the associations 
list to create the punchline: "Upselling their way to a sharper 
disappointment.“

Angle: "Now, viewers can pay more to witness their favorite cat videos 
        in stunning clarity.”

Putting it all together: "YouTube experiments with a new "1080p Premium" 
                         option, offering higher-quality video for 
                         Premium subscribers. Now, viewers can pay more 
                         to witness their favorite cat videos in stunning 
                         clarity – upselling their way to a sharper 
                         disappointment."
```

By breaking down the monologue joke creation process into sections, we can guide ChatGPT to perform more advanced tasks. This approach allows the model to focus on specific components of the joke, ensuring a more structured and coherent output. The resulting monologue jokes can be tailored to the user's requirements, making them suitable for various applications, such as late-night TV shows, stand-up comedy, or humorous writing.

## Conclusion

In summary, using ChatGPT to craft monologue jokes involves breaking down the process into several steps:

1. Punch line creation: Develop a topic based on real news events.
2. Punchline development: Identify handles and associations.
3. Combine associations to create the punchline.
4. Connect the topic and punchline using an angle.

By guiding ChatGPT through these steps, we can effectively leverage the model's capabilities to produce humorous monologue jokes. This approach demonstrates the potential for using large language models like ChatGPT in more advanced applications, such as scriptwriting or comedic content generation. As the technology continues to improve, we can expect even better results in creating monologue jokes and other forms of engaging content tailored to specific requirements and contexts.