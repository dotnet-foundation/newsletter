# Newsletter

Welcome to the .NET Foundation Newsletter Repository. This repo is used to manage and create newsletters sent to the members of the foundation and the general interested public. You can [sign up for the .NET Foundation newsletter here.](http://eepurl.com/dhL_qb)

## Submission

Every month we will create an issue for the upcoming newsletter as well as a markdown file to contain the news. News should be submitted as a pull request to [the current newsletter markdown file](https://github.com/dotnet-foundation/website/blob/master/input/blog/posts/_current-newsletter-draft.md).

<img width="796" alt="Screen Shot 2019-07-18 at 11 34 08 AM" src="https://user-images.githubusercontent.com/19977/61482800-503a8100-a950-11e9-9013-67dddc0cd832.png">

_Pro tip: You can submit your news through the website by clicking the edit icon when viewing the newsletter markdown file. Just make your edits and when you commit, GitHub will walk you through creating a pull request._

Please append your news to the appropriate section. For Foundation Project News, please append your news to the section labeled `.NET Foundation Project Updates`. Also, please add a line in your PR message that says `Related: #123` where `123` is the issue number of newsletter issue (_Pro Tip: If you type `#` and start typing "news" GitHub will list issues related to the newsletter_). That gives us a nice digest for submissions.

It's a simple format.

Start with an H3 heading (aka `###`) that is linked to your news item. So if you're writing about a new release, then link the heading to the release. If you're writing about a new project, link to the repository.

Follow the heading with your project news. Feel free to include images and links.

_Pro tip on images_: Go to a [new issue form](https://github.com/dotnet-foundation/newsletter/issues/new), then drag and drop an image into the body of the issue. It will upload the image and when it's done, present the markdown for the image. Copy and paste that into your news item. __Don't save the issue!__ The image will remain.

Here's a template you can use.

```md
### [Headline for your news](https://URL-TO-THE-SUBJECT-OF-THE-NEWS)

Write all your content here using Markdown. See the following guide: https://help.github.com/en/articles/basic-writing-and-formatting-syntax

You might have a nice ![image here](https://URL-TO-IMAGE/).

Sometimes it's nice to end with a:

* [bulletted](url-to-resource)
* [list](url-to-resource)
* [of linked resources](url-to-resource)
```

## Who may submit news?

While we expect project maintainers to submit interesting news about their projects, we welcome anyone in the .NET community to submit news related to the Foundation or Foundation Projects.

## Scheduling

We send out the newsletter the last week of each month. We try and set a deadline for project news one week before the end of the month.

The contents of the newsletter are also published to the [.NET Foundation Blog](https://dotnetfoundation.org/blog).
