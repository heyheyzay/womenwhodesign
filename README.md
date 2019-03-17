# Women Who Design

Women Who Design is a Twitter directory of accomplished women in the design industry. It aims to help people find notable and relevant voices to follow on Twitter by parsing Twitter bios for popular keywords.

Here are some things Women Who Design can help you with:

- **Use [proporti.onl](https://www.proporti.onl/) to check the ratio of the people you follow on Twitter.** If you're following more men than women, use this project to follow new women and diversify the voices in your feed. Be aware that a feed of white women is not diverse.
- **If you're a hiring manager, use this project to find candidates.** Examine the ratio of senior men to senior women in your organization. Are women of color equally represented? Consider hiring women into promotions above their current role.
- **If you're organizing a conference, use this project to find speakers.** Ensure that the women's speaking slots are as prominent as the men's. Are women of color equally represented? Consider reaching out to women who have never given a talk before.
- **If you have a podcast, use this project to find new guests.** Be mindful of interruptions and ensure that your women guests get equal speaking time. Are women of color equally represented? Consider inviting women who don't already have an audience.

## Forking this project

Women Who Design is happy to support new directories highlighting underrepresented or marginalized groups by providing its source code.

### Prerequisites

This project requires API keys from [Twitter](https://twitter.com) to populate the profile data and [Seeker](https://seeker.company) to populate the job posts.

Seeker is optional. To run this project without Seeker:

1. Delete the `gatsby-source-seeker plugin` (lines 14-19) from the `gatsby-config.js` file
2. Delete the entire `gatsby-node.js` file
3. Delete the `src/pages/jobs.js` file
4. Remove the link to the jobs page from the `src/components/nav` file

Twitter is required. To register your new project with Twitter:

Create an app on the [Twitter developer dashboard](https://developer.twitter.com/en/apps). Select the "Read only" access option.
