# 🎉 How to build an Interactive Resume GPT

## 🛈 Purpose
During interviews, I often found myself forgetting important points or not articulating my answers well because I don't have a response to every possible question committed to memory. Therefore, I have created a Custom GPT to enable recruiters and hiring managers to gain deeper insights into my personality, qualifications, knowledge, and experience in a fun and interactive way.

## 🤷🏽 How It Works
* Share the link to your custom GPT App with recruiters and hiring managers.
* They must have a GPT Plus subscription from [OpenAI](https://www.openai.com/).
* They can ask interview questions to delve into your professional journey and get to know you.
* Your app's responses are limited to the information on your resume and other data that you provide.

  

https://github.com/BoredApps/resume-chat/assets/154591403/0105e77e-8057-4d97-8631-0a9e41b73e58


<br>
<br>
<br>
⚠️ These instructions assume that you already have a GPT Plus account and are familiar with building GPT Apps.<br>
⚠️ The provided documentation is just an example. You will need to edit it or create your own.<br>
⚠️ You are not limited to what I've done here; I'm simply sharing my work to help kickstart some ideas.<br>
<br>
<br>
<br>

# 👷 How to Build It!

## 1️⃣ The Prompt
The first step is to provide your custom GPT with direction and purpose. You can fine-tune it as you wish, but you need to define the parameters by which it should operate and the data it should draw from. 
I've provided a sample prompt sheet above titled "Directions_sample.pdf" to use as a starting point.

## 2️⃣ Upload the Data
Since this app represents you as if you are being interviewed, you need to provide it with the data from which to draw answers. I've configured my version of the app to draw from four main files (docx or PDF):

1. **Resume.pdf:** As a resume-based app, starting with a solid resume is essential. Since I'm applying for two different roles, I've uploaded two different resumes, one for each role, and formatted them for application tracking systems. If you need help with resume formats, I have [free resume templates here](https://github.com/BoredApps/Free-Resume-Templates). Download the sample resume above. 

3. **Skills.pdf:** I created a document that lists skills categorized as "Familiar with" (understand or learning), "Proficient with" (hands-on in a production environment), "Experienced with" (significant experience),and "Expert." You can categorize them as you want or choose not to do this step. Download the sameple skills pdf above. 

4. **Questions.pdf:** I simply asked Chat GPT for examples of common interview questions for the positions I am applying for, supplemented it with information from jobs I'd applied to, memories from previous interviews, and I created a document of answers to those questions. Download an example of industry specific questions above. 

5. **LinkedIn.pdf:** You will need to [export your LinkedIn profile as a PDF](https://www.linkedin.com/help/linkedin/answer/a541960/save-a-profile-as-a-pdf?lang=en-us&intendedLocale=en), and upload it to your custom GPT.

6. I also uploaded the **Directions.pdf** with the original prompts for it to remind itself of its role, and from where it will draw the data.

<b>Make sure to edit your prompts and directions to make it draw from whatever files you've uploaded and explain why it should do that.</b>

## 3️⃣ Additional tips
* Test your resume chat. You may need to fine tune a few things or add custom instructions to ensure that it best represents you.
* It has a tendancy to repeat the question before answering. I don't like that. It comes off as filler to me. I've instructed mine to stop doing that, and just answer directly. 
* I prefer to keep my resume chat only for those with the link, but you may want to make yours public. It's up to you.
* DO NOT include any personal information, phone number, address, or contact info of any references in your data sheets. 
<br>
<br>
<br>
<hr>

### Credits:
This article was written with the assistance of <strong><a href="https://chat.openai.com/g/g-dH2mK7Um0-wordsmith">WordSmith, a custom ChatGPT Plus application</a>, </strong>and thoughtfully edited by a human to ensure the highest quality and authenticity. 
<hr>
* Visit us at <a href="https://BoredApss.ai">BoredApps.ai</a>
