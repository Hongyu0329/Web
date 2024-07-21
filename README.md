
# Web
Webpage development project

Below are notes collected from [Mmdn web docs: Getting start with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web), only for self-learning purpose.

## Files

### [Where should your website live on your computer?](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Dealing_with_files#where_should_your_website_live_on_your_computer)

When you are working on a website locally on your computer, you should keep all the related files in a single folder that mirrors the published website's file structure on the server. This folder can live anywhere you like, but you should put it somewhere where you can easily find it, maybe on your Desktop, in your Home folder, or at the root of your hard drive.

1. Choose a place to store your website projects. Inside your chosen place, create a new folder called `web-projects` (or similar). This is where all your website projects will live.
2. Inside this first folder, create another folder to store your first website in. Call it `test-site` (or something more imaginative).

### [An aside on casing and spacing](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Dealing_with_files#an_aside_on_casing_and_spacing)

You'll notice that throughout this article, we ask you to name folders and files completely in lowercase with no spaces. This is because:

1. Many computers, particularly web servers, are case-sensitive. So for example, if you put an image on your website at `test-site/MyImage.jpg` and then in a different file you try to invoke the image as `test-site/myimage.jpg`, it may not work.
2. There are many ways in which using spaces in file names create issues:
    - When you invoke commands in the terminal, you have to put quotes around file names with spaces in them, or the path will be interpreted as two separate items.
    - Some programming languages (e.g. Python) do not work well with spaces in file names if these files are modules to be imported.

### [What structure should your website have?](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Dealing_with_files#what_structure_should_your_website_have)

Next, let's look at what structure our test site should have. The most common things we'll have on any website project we create are an index HTML file and folders to contain images, style files, and script files. Let's create these now:

1. **`index.html`**: This file will generally contain your homepage content, that is, the text and images that people see when they first go to your site. Using your text editor, create a new file called `index.html` and save it just inside your `test-site` folder.
2. **`images` folder**: This folder will contain all the images that you use on your site. Create a folder called `images`, inside your `test-site` folder.
3. **`styles` folder**: This folder will contain the CSS code used to style your content (for example, setting text and background colors). Create a folder called `styles`, inside your `test-site` folder.
4. **`scripts` folder**: This folder will contain all the JavaScript code used to add interactive functionality to your site (e.g. buttons that load data when clicked). Create a folder called `scripts`, inside your `test-site` folder.

### [File paths](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Dealing_with_files#:~:text=on%20the%20web.-,File%20paths,-To%20make%20files)

We need file path to make files contact with each other.

Below is a html code that display images we choose in the folder

```html
<!doctype html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>My test page</title>
  </head>
  <body>
    <img src="$/file/path" alt="My test image" /> 
    <!-- used to import images -->
  </body>
</html>
```




## HTML Basics

