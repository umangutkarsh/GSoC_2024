# Google Summer of Code 2024, RocketChat

<div align="center">
    <a href="https://summerofcode.withgoogle.com/projects/#6521788818784256"><img src="https://i.imgur.com/pgkUceb.png" width="650" alt="google-summer-of-code"></a>
    <br>
    <b> 
        <p>
        Discover the latest news from your favorite sources, right within Rocket.Chat, with the News Aggregation App.
        </p>
    </b>
</div>


I worked on a project called [News Aggregation App](https://github.com/RocketChat/Apps.News-Aggregation) which is an app provides a centralized platform for seamless access to curated news content within the chat environment.

I would maintain this repository as the final report summary of my GSoC 2023 project and a quick guide for all future GSoC aspirants.


## ⭐ Project Abstract
The News-Aggregation project aims to develop a Rocket.Chat app that collects and displays news from top websites like TechCrunch. It will aggregate data using APIs and RSS feeds, allowing users to configure their preferred sources and categories. The goal is to provide a daily news feed within Rocket.Chat, enhancing the platform by offering organized and curated news content. The project focuses on Rocket.Chat app development involves technical data collection, categorization, and presentation challenges.


## 🚢 Deliverables
- Implementation of a robust news collection mechanism capable of gathering articles from various sources such as TechCrunch and other top websites, utilizing different logic to collect news from sources with APIs and RSS feeds.
- Development of a user-friendly interface for presenting news articles in a "newspaper" or "news feed" format within the Rocket.Chat environment, including summaries of articles and links to full content.
- Incorporation of a categorization system to organize news articles based on predefined categories or user-defined tags, providing flexibility and customization for users.
- Complete configurability of news sources and categories, allowing users to customize their news feed according to their preferences and interests.

These deliverables aim to provide users with a comprehensive News Aggregation App that offers convenient access to daily news from various sources within the Rocket.Chat ecosystem.



## 🚀 Contributions
### Pull Requests

<div align="center">

| PR Link   | Description  |
| :-----------: | :------------------------------------:|
| [PR #2](https://github.com/RocketChat/Apps.News-Aggregation/pull/2) | [NEW] initial setup of rc-app<div> |
| [PR #3](https://github.com/RocketChat/Apps.News-Aggregation/pull/3) | Direct message for user onInstall |
| [PR #4](https://github.com/RocketChat/Apps.News-Aggregation/pull/4) | [FEAT]: Slash commands code setup |
| [PR #5](https://github.com/RocketChat/Apps.News-Aggregation/pull/5) | Helper message with slash command - `/news help` |
| [PR #6](https://github.com/RocketChat/Apps.News-Aggregation/pull/6) | NewsSource & NewsItem base class setup |
| [PR #7](https://github.com/RocketChat/Apps.News-Aggregation/pull/7) | App Command Setup (Add slash command options) |
| [PR #8](https://github.com/RocketChat/Apps.News-Aggregation/pull/8) | Setup Prettier |
| [PR #9](https://github.com/RocketChat/Apps.News-Aggregation/pull/9) | News-Item Persistence Class |
| [PR #10](https://github.com/RocketChat/Apps.News-Aggregation/pull/10) | Subscription persistence and Subscription Interface |
| [PR #11](https://github.com/RocketChat/Apps.News-Aggregation/pull/11) | Integrate Save-News feature to command utility |
| [PR #12](https://github.com/RocketChat/Apps.News-Aggregation/pull/12) | Get-News on demand from persistence (`/news get`) |
| [PR #13](https://github.com/RocketChat/Apps.News-Aggregation/pull/13) | NewsFetch Service setup |
| [PR #14](https://github.com/RocketChat/Apps.News-Aggregation/pull/14) | ElementBuilder Setup |
| [PR #15](https://github.com/RocketChat/Apps.News-Aggregation/pull/15) | BlockBuilder setup |
| [PR #16](https://github.com/RocketChat/Apps.News-Aggregation/pull/16) | UI Kit interaction setup
| [PR #17](https://github.com/RocketChat/Apps.News-Aggregation/pull/17) | Register processors + NewsDeliveryService
| [PR #18](https://github.com/RocketChat/Apps.News-Aggregation/pull/18) | Refactor + Create Services + Display News
| [PR #20](https://github.com/RocketChat/Apps.News-Aggregation/pull/20) | Subscribe modal uikit
| [PR #21](https://github.com/RocketChat/Apps.News-Aggregation/pull/21) | Unsubscribe news
| [PR #22](https://github.com/RocketChat/Apps.News-Aggregation/pull/22) | Integrate more News-Sources
| [PR #23](https://github.com/RocketChat/Apps.News-Aggregation/pull/23) | Settings to configure News Sources
| [PR #24](https://github.com/RocketChat/Apps.News-Aggregation/pull/24) | News Categorization
| [PR #26](https://github.com/RocketChat/Apps.News-Aggregation/pull/26) | Deliver News based on Subscribed Categories
| [PR #27](https://github.com/RocketChat/Apps.News-Aggregation/pull/27) | Delete Old News periodically
| [PR #28](https://github.com/RocketChat/Apps.News-Aggregation/pull/28) | Update ReadMe

</div>

### My overall contributions to RocketChat
Besides Apps.News-Aggregation I also contributed to other RocketChat Projects like [EmbeddedChat](https://github.com/search?q=type%3Apr+author%3Aumangutkarsh+is%3Apublic+++repo%3ARocketChat%2FEmbeddedChat+&type=pullrequests), [Apps.Whiteboard](https://github.com/search?q=type%3Apr+author%3Aumangutkarsh+is%3Apublic+++repo%3ARocketChat%2FApps.Whiteboard+&type=pullrequests).



## 🎓 Mentor
A big big thank you to my mentor for the guidance before and throughout GSoC. 🙏 
I learned beyond GSoC from him and am forever grateful to be mentored by him.
- **Abhinav Kumar** - [GitHub](https://github.com/abhinavkrin). [LinkedIn](https://www.linkedin.com/in/abhinavkrin/)



## 🔗 Links
- Read my Apps.News-Aggregation project proposal that got me accepted to GSoC [here](https://docs.google.com/document/d/1AZPcE2iTYSojTyJKhDTNrt1MGP6UYzxIXsf37ckXxIk/edit?usp=sharing).
- I also complemented it with Figma designs. Check them out [here](https://www.figma.com/design/pDVuEuWU8KWTX7HntOZ5FV/News-Aggregator-app?node-id=0-1).



## ❤️ Support
Learned something new today? Reciprocate the love. ⭐ this repo for good karma.



## 💬 Connect With Me    
Want to discuss about GSoC / Rocket.Chat / Open-source ? Let's connect!
<div align="center">

| **Contributor** | Umang Utkarsh |
|:--------------------|:-------------------|
| **Organization** | [Rocket.Chat](https://rocket.chat/) |
| **Project** | [Apps.News-Aggregation](https://summerofcode.withgoogle.com/programs/2023/projects/sUXGt89N) |
| **GitHub** | [@umangutkarsh](https://github.com/umangutkarsh) |
| **LinkedIn** | [umangutkarsh](https://www.linkedin.com/in/umang-utkarsh-568a841b6/) |
| **X** | [@umangutkarsh_](https://x.com/umangutkarsh_) |
| **Email** | <a href="mailto:umangutkarsh0024@gmail.com">umangutkarsh0024@gmail.com</a> |
| **Rocket.Chat** | [umang.utkarsh](https://open.rocket.chat/direct/umang.utkarsh) |
       
</div>


