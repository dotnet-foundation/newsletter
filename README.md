# Newsletter

Welcome to the .NET Foundation Newsletter Repository. This repo is used to manage and create newsletters sent to the members of the foundation and the general interested public.

## Submission

Foundation/Project news should be submitted as a pull request to the existing newsletter markdown file. The file will be named for the month in a folder with the name of the year. For example, the July 2019 newsletter is in a file named [`2019/07.md`](blob/master/2019/07.md).

_Pro tip: You can submit your news through the website by clicking the edit icon when viewing the newsletter markdown file. Just make your edits and when you commit, GitHub will walk you through creating a pull request._

Please append your news to the section labeled `.NET Foundation Project Updates`.

It's a simple format.

Start with an H3 heading that is linked to your news item. So if you're writing about a new release, then link the heading to the release. If you're writing about a new project, link to the repository.

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
