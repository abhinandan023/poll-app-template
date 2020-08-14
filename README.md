# Poll App Template

| [Documentation](./wiki/Home.md) | [Deployment guide](./wiki/Deployment-guide.md) | [Architecture](./wiki/Solution-overview.md) |
| ---- | ---- | ---- |

Poll is a custom [Teams message extension](https://docs.microsoft.com/en-us/microsoftteams/platform/messaging-extensions/what-are-messaging-extensions) app that enables users to quickly create and send polls in a chat or a channel to know their team’s opinion. Use this template in Meetings along with group and channels. Poll app is supported across all platforms – Teams desktop, browser, iOS, and Android clients. It is built on Microsoft 365 Action platform (an extension of [Kaizala Action platform](https://docs.microsoft.com/en-us/kaizala/developer-platform))

![Poll Template compose message screen](./wiki/images/PollTemplateCompose.gif)

### Key features
* **Poll creation:** Easily create Polls, click **Menu** (…) below the box where you type your message. Enter your poll question in the Poll app followed by at least two choices for answers. You can add as many as 10 choices to a poll. Set a due date for the poll and restrict who can see poll results in **Settings**. When you are done, click **Send Poll** to publish your poll.

![Poll Template Creation screen](./wiki/images/PollTemplateCreation.png)

* **Poll response:** To respond to a poll, choose an option on the poll card and click **Submit Vote**. As people in your group or channel vote, you will see updates to the response summary on the poll card.

![Poll Template Submit screen](./wiki/images/PollTemplateSubmit.png)

* **Poll aggregate results:** To see the results of your poll, click View Result. Participation Summary shows the response list along with the participants’ choices. The list of people who didn’t vote on the poll is in the adjacent tab. Click Back to return to the result summary view. Download an image of your poll’s results or a .csv file of the response list by selecting **Download**.

![Poll Template Detail screen](./wiki/images/PollTemplateDetail.png)

## Get started

Begin with the [Solution overview](./wiki/Solution-overview.md) to read about what the app does and how it works.

When you're ready to try out Poll, or to use it in your own organization, follow the steps in the [Deployment guide](./wiki/Deployment-guide.md).

## Feedback

Thoughts? Questions? Ideas? Share them with us on [Teams UserVoice](https://microsoftteams.uservoice.com/forums/555103-public)!

Please report bugs and other code issues [here]().

## Legal notice

This app template is provided under the [MIT License](./LICENSE) terms.  In addition to these terms, by using this app template you agree to the following:

- You are responsible for complying with all applicable privacy and security regulations related to use, collection and handling of any personal data by your app. This includes complying with all internal privacy and security policies of your organization if your app is developed to be sideloaded internally within your organization.

- Where applicable, you may be responsible for data related incidents or data subject requests for data collected through your app.

- Any trademarks or registered trademarks of Microsoft in the United States and/or other countries and logos included in this repository are the property of Microsoft, and the license for this project does not grant you rights to use any Microsoft names, logos or trademarks outside of this repository. Microsoft’s general trademark guidelines can be found [here](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general.aspx).

- Use of this template does not guarantee acceptance of your app to the Teams app store. To make this app available in the Teams app store, you will have to comply with the [submission and validation process](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/appsource/publish), and all associated requirements such as including your own privacy statement and terms of use for your app.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.