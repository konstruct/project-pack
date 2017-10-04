# Project Pack

Keeping a consistent pack structure will help developers to quickly find and work with assets across projects and teams.

## Project Pack structure

Please ensure that you adhere to the following structure:

- site.yml
- 1--content/
- 2--design/
  - open files/
  - jpg screens/
- 3--assets/
  - web-icons.ai
  - icons.ai
  - asset-sheet.yml
  - images/
    - site/
    - content/

## Providing Information

## site.yml

This file contains all of the access information the developer will need during the course of the project.

You simply fill in the blanks with the details provided by the client / client IT person.

If hosting is provided by Crio, you can simply state this in the hosting provider field, and leave the rest blank.

### Providing content

Content generally comes in many forms and formats, and we can deal with it as it comes, but below is our preferred content structure:

- frontpage.doc/pdf
- about.doc/pdf
- contact.doc/pdf
- articles/
  - article-name.doc/pdf
- services/
  - service.doc/pdf

**Note:** Please avoid using excell for content. It's very hard to work with and keep track.

**IMPORTANT** Don't put images in the content document **ever**. Please reference to them with a tag below:

`[IMAGE: 3--assets/images/content/about.jpg]`

### Providing designs

We require both the design's open files (psd, ai) as well as the individual jpg renders of each page.

### Providing assets

#### General rules

- Always ensure that your assets are prepared properly. Expand your layers and convert text properly.
- Keep your naming of assets consistent and user friendly.
- Give the developer all of the information - if you don't tell us about a thing, we won't do that thing.

#### web-icons.ai

The `web-icons.ai` file contains artboards for the common icon sizes that are generally required for websites.

You can simply fill them in and save the ai file. We can render out the icons ourselves.

Don't change the artboard names as they contain the required filenames for the icons.

#### icons.ai

The `icons.ai` file will contain all of the icons that need to be displayed within the project.

You need to add an artboard for each individual icon and name the artboard in the following pattern:

- `icon--burger`
- `icon--arrow-left`
- `icon--social-facebook`
- `icon--social-twitter`

You can provide the ai file as is, and we will render them out.

#### asset-sheet.yml

This file contains all of the specific information that will help the developer to provide his work as near to your design as possible.

You can expand on this document as much as you want, by simply following the YAML formatting rules.

#### images

You can save out any images into this folder. Please organise your images in groups and keep naming consistent and friendly.

##### Common image types

- JPG: For photos and complex images
- PNG: For images that require transparent background. Generally best to keep this format for simpler images
- SVG: For icons, logos and illustrations.
