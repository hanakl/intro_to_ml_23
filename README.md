# ICME Summer Workshop Website Template
This repository is intended for ICME Summer Workshop Instructors, to facilitate
website creation. The steps laid out below are intended to guide you through
the process of creating a publicly viewable [Github
Page(s)](https://pages.github.com/) that are templated with ICME Summer Workshops in mind. It is the author's belief that by creating a unified template to work from, that students can focus more on learning the content of the courses and worry less about how to navigate through each course's custom website UI; this is important since many students involved with Summer Workshops tend to take multiple courses.


## Filling in the contents of the website
The file `index.md` is really the file that you want to look at and modify when
changing your website.

Please replace `TODO(instructor)` comments with the relevant text that is being
requested to be filled in. If you're wondering about a complete listing of
`TODO`'s, simply navigate to your working directory in a Command Line Interface
and execute the following command:

```
grep -r 'TODO(instructor)' *
```

This will then pull up a listing of remaining to-do items that need to be
cleared before the website is ready for students to view/use.

## Previewing your website
You'll want to get an idea for what the website currently looks like as you
modify it. There are is a set-up step and two recurring steps that must be done
with each change you wish to make. 

### Initial Github Pages Set-up
To set-up your website initially,
navigate to the Github-UI for your repository (e.g. something like
`github.com/<username>/<repository-name>`), then click the `settings` pane
toward the top-right corner of the page, then click `pages` within the bottom of
the left pane, then under the **Source** section select that you wish to use
`main` branch and hit "save". You should now see text-appear within the page
that says, "Your site is ready to be published at: <url>".

### Previewing Changes
When you make changes to your website, one way to view your changes would be to
actually publish them to your website and inspect the live URL.
  * Commit changes to Github _and push_ said changes to your online repository.
    This would be done via a sequence of commands, e.g.
      * `git add 'my_recently_modified_file'`
      * `git commit -m 'Insert a helpful commit message here.'`
      * `git push` (possibly followed by an authentication step)
  * User your web-browser to navigate to the following link:
  ```
  <github_username>.github.io/summer-workshop
  ```
  
## Website Structure
### Modifying `index.md`
We mentioned previously that `index.md` is the backbone of the website; please
take your time to go through this raw-file and replace / update the contents
with information that is pertinent to your workshop.

There are, however, some additional sources of input used when constructing the
website.

### The left-panel of the website
There is some meta-data that needs to get updated within the left panel of the
site. Please go through the following steps

  * Within `_site/index.html`:
    * Update _when_ your workshop is occurring (line 41)
    * Update any _downloads_ that are relevant to your workshop (line 45); copy-paste line-45 multiple times and update `href` tag to point to workshop file-content.
      * To be explicit, you should place your workshop content in an
appropriately named file within the `docs/` folder, making sure to commit and
push your changes to GitHub. Then, whatever you chose for your filename, make
sure to insert that filename on line 45.
    * Update your name to appear as Lecturer on line 60, and on this same line
also replace `SUNET` with your relevant `SUNET` (or more generally, your email
address).

# The Minimal theme

[![Build Status](https://travis-ci.org/pages-themes/minimal.svg?branch=master)](https://travis-ci.org/pages-themes/minimal) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-minimal.svg)](https://badge.fury.io/rb/jekyll-theme-minimal)

*Minimal is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/minimal), or even [use it today](#usage).*

![Thumbnail of minimal](thumbnail.png)

## Usage

To use the Minimal theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    theme: jekyll-theme-minimal
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```



## Customizing

### Configuration variables

Minimal will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
logo: [Location of the logo]
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

### Layouts

If you'd like to change the theme's HTML layout:

1. [Copy the original template](https://github.com/pages-themes/minimal/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
2. Create a file called `/_layouts/default.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

## Roadmap

See the [open issues](https://github.com/pages-themes/minimal/issues) for a list of proposed features (and known issues).

## Project philosophy

The Minimal theme is intended to make it quick and easy for GitHub Pages users to create their first (or 100th) website. The theme should meet the vast majority of users' needs out of the box, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.

## Contributing

Interested in contributing to Minimal? We'd love your help. Minimal is an open source project, built one contribution at a time by users like you. See [the CONTRIBUTING file](docs/CONTRIBUTING.md) for instructions on how to contribute.

### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/minimal`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` one before the test script will work.
