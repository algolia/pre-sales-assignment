# Solutions Consultant Hiring Assignment
If you're looking to apply as a Solutions Consultant with the Solutions Team at [Algolia](https://www.algolia.com), welcome :).

## Questions
Please begin by answering the below set of mock pre-sales questions; these are similar to ones you would encounter in your day-to-day while working at Algolia. Just please be sure not to not fork this repository to create your assignment. Doing so will wake a bot that prints out your code, immediately sends it to the shredder, and archives your application in our applicant tracking system. And anyway we’d rather give everyone an equal shot to show us what they can do.

--------------

### 1.
Good morning,

I'm new to search engines, and there are a lot of concepts I'm not educated on. To make my onboarding smoother, it'd help if you could provide me with some definitions of the following concepts:
* Records
* Indexing
* SLA
* Facets

I'm also struggling when setting up the option "Ordered/Unordered" of the setting `AttributesToIndex`. Could you help me understand how it works?

Cheers,
George

Product Manager

--------------

### 2.
Hello,

I had a look at the article you sent me https://blog.algolia.com/how-algolia-tackled-the-relevance-problem-of-search-engines/ 

After reading it, I'm still not convinced that the approach you have is better than the approach of Solr that is using boosts/coefficients. In addition to this, it also feels as though the boosts allow for better ways to inject ads to promoted content?

It may be because of my engineering background, but using float-value boosts seems like it's a lot more precise than your approach. And search engines are all about precision.

Am I missing something here? Can you convince me of the opposite?

Talk Soon!

Angela

Sr. Developer

--------------
### 3.
Hi there,

I love Algolia, but there's something critical for us that may be a deal-breaker for us.

As you know, we allow our customers to search into their own personal emails. For obvious security reasons, we want to make sure only the owner of a set of emails can access to these emails.

You told me about your "Secured API Key" feature, but:

1. I'm not convinced it's actually secure. Can you explain the technical reasons explaining why this feature is secure?
2. I can't figure out how to make it work. Can you guide me through the implementation steps?
3. How long would it take my developers to do this?
4. Does Algolia have a way the API can list all of the API keys that have been generated?

John

Chief Product Officer

--------------
### 4.
Greetings,

We’re considering Algolia and one of the things that we need is to have location search. Let me lay out what we need:

A user can search through a list of locations (for example, like you can do on Google Maps). Then, after selecting a location, all of the products will then be filtered based on whether the product belongs to that location.

Is this something that can be done with Algolia?

Laura

Search Developer

--------------

### 5.
Hello,

I am just ramping up on my trial with Algolia. I can see that the dashboard can be used to import records, however I am having some difficulty figuring out how to import a large set of records through the API in {Python/JavaScript/Java/etc}. Could you provide me with a source sample on how this could be done, or if it’s possible?

Kyle

Chief Technical Officer

 **NOTE**: For this answer, use any language of your choice. Keep in mind, we love to see people that are willing to get out of their comfort zone, and may use a language they aren't exactly familiar with. 

## Product Challenge
* *Step 1*: Sign Up on for an Algolia account
For your company name, please put “Solutions Consultant Assignment” so we can ensure you do not get the sales team reaching out.
* *Step 2*: Imagine 3DR changed their name to "Best Drones Company", show us how you'd handle accommodating for this change in Algolia.  
  **NOTE**: This can be accomplished either before, or after uploading your data to Algolia. Get creative and show us what you think is the best way to accommodate for this change.
* *Step 3*: Upload either the Best Buy JSON or CSV dataset utilizing an API client of your choice.
* *Step 4*: Configure search relevance.  
  **NOTE**: This is open for personal interpretation, but given examples on our website and the documentation, use the tools at your disposal to learn as much as you can about using our amazing product! There's some great information in the references below!
* *Step 5*: Similar to what you'd find in a real world scenario here, ensure that if a user searches for "Maroon cellphone" we still return results.
* *Step 6*: Ensure that if a user searches for "cellphones" that we show a series of Samsung phones to the first 3 positions.
* *Step 7*: Have fun, and please keep track of any scripts you write to accomplish this challenge. We want to see your creativity and tenacity to solve challenges at Algolia.

   * **BONUS**: Put together a basic site that will return search results from your index. This doesn't need to include any focus on the UX, it just needs to return results. You can use any libraries you'd like to accomplish this challenge.

## Challenge Submission
Please save your answers in a Word doc, and send them to your main point-of-contact at Algolia to give us ample time to review your answers. Any scripts you write, please share with us via a [Private Gist](https://gist.github.com/), and if you tackle the challenge share it with us through [GitHub Pages](https://pages.github.com/).

## References
* [Algolia Docs](https://www.algolia.com/doc/)
* [Algolia Community](https://community.algolia.com)
* [InstantSearch Workshop](https://github.com/algolia/instantsearch-workshop)
