# Prework - *Random Color Generator*

Submitted by: **Mingyi Gao**

**Random Color Generator** is an app that can change its background color randomly when you click the "Change" button.

Time spent: 3 hours spent in total

## Required Features

The following **required** functionality is completed:

- [✔️] Users are see a screen with three labels and a button
- [✔️] Tapping the button changes the screen color to a random color

## Video Walkthrough
<div>
    <a href="https://www.loom.com/share/2bc231e3827a4818a0e0007f5a07b703">
    </a>
    <a href="https://www.loom.com/share/2bc231e3827a4818a0e0007f5a07b703">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/2bc231e3827a4818a0e0007f5a07b703-with-play.gif">
    </a>
  </div>

## App Brainstorming
**Twitter**
 * Very concise compared to those all-in-one apps.
 * The scrolling is smooth and logic is simple.
 * Overall, it's a great social media app, although it's becoming increasingly complex and bug-prone, especially after becoming X.🤣

**Apple Music**
 * Similar to Twitter, it's a lightweight app with focused functionalities.
 * The UI and UX design are very nice - not too fancy, and it's easy to get started.
 * No ads is a big plus.

**Amex**
 * Its UI design is more modern compared to other financial apps like BoA.
 * The loading of pages is quite fast.
 * I have't found any bugs.

**Gmail**
 * Simple and easy to use.
 * The UX design is much better than that of Microsoft products. I can't quantify the experience, but using Google apps feels smoother compared to Microsoft apps.

**An app idea that I would like to build**
 * It's called GPT Vault.
 * The initial objective of this project is to serve as a secure repository for storing answers generated by ChatGPT. One of the challenges encountered by ChatGPT is its occasional difficulty in retaining chat history. By utilizing this repository, we can ensure that the valuable responses provided by ChatGPT are preserved and readily accessible for future reference.

 * Furthermore, this repository offers an additional advantage in the form of a filtering feature. This feature enables us to categorize and organize the answers in a more efficient and structured manner. By applying appropriate filters, we can easily retrieve specific responses based on relevant criteria such as topic. This enhanced organization contributes to an improved user experience and facilitates more effective utilization of the information generated by ChatGPT.
    


## Notes

Describe any challenges encountered while building the app.

I had a problem connecting a button to logic. At first I did't create an `@IBAction`, so it did't function as expected. After I deleted the old one and correctly created an `@IBAction`, it encountered an error. Initially, I was stuck. After thoroughly going through the guide, I realized that the error might be caused by the connection - the old code was deleted, but its connection was still there. So I deleted the old connection in the Connection Inspector. Finally, it ran without errors or bugs and it's functioning as expected.

## License

    Copyright [2023] [Mingyi Gao]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
