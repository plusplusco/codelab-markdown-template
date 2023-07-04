# Codelab Markdown Template
Some of the information in this template was taken from Google Codelabs' official docs in their GitHub repository, which you can check out [here](https://github.com/googlecodelabs/tools/blob/main/FORMAT-GUIDE.md).

---
id: your-apps-id
summary: Your Codelab's description.
status: [published]
authors: John Doe
categories: Category 1, Category 2
tags: my-tag,
feedback link: https://[...].com
analytics account: your-analytics-account-id

---
## Setting up your Metadata
Feel free to replace this text and the heading's title with whatever makes the most sense. Here are some formatting tips for your Codelab:

You are free to add your own metadata here if you'd like but certain key/value pairs are reserved for specific codelab publishing features. The current list of reserved metadata terms are:

-   **summary:**  A short summary of the codelab that will be shown in the codelab browser UI.
-   **id:**  The name of the folder that will be generated once you export the markdown file via claat.
-   **categories:**  A single, top-level category that will be used to group codelabs by platform. Categories are normally curated by an organization (e.g. we have a set we use for the Google Codelabs site) but each publisher is free to use this value at their discretion.
-   **environments**: A tag that allows use to output some codelabs for a specific environment. All codelabs default to the "Web" environment but given some hardware constraints we might only want to generate them for a "Kiosk" environment where we know people will have the right hardware.  
    You can also use this to target specific events, for instance:  
    "Web, polymer-summit" (without quotes)
-   **status:**  One or more of (Draft, Published, Deprecated, Hidden) to indicate the progress and whether the codelab is ready to be published. 'Hidden' implies the codelab is for restricted use, should be available only by direct URL, and should not appear on the main index page.
-   **feedback link:**  The URL that the student should be sent to when they click on the feedback link to report a bug in the codelab.
-   **analytics account:**  This allows you to specify a custom Google Analytics ID for your codelab. If no ID is specified, it defaults to a global codelabs analytics account.
-   **tags:**  Add relevant tags to make your codelab easily found.
-   **authors:**  Indicate the author(s) of this specific codelab.
## Headers and styles (this is a Header 2)
### This is a Header 3
#### This is a Header 4
##### This is a Header 5
###### This is a Header 6
This is a normal paragraph
**This is a bold phrase**
*This is an italic phrase*
~~This is a strikethrough phrase~~

> You can add quotes like this

    # You can also add code
    print('Hello World!')
    
|Title| Description |
|--|--|
| Table | You can also add tables |
| Row | Add as many rows as you want |

[You can add links](https://plusplus.co)

You can add lists like this:
- My first item
- My second item

Or like this:
1. My first item
2. My second item

![image embed](https://google.com)