# Dossier

Keeping a consistent pack structure will help developers to quickly find and work with assets across projects and teams.

---

## Project Structure

Projects are laid out in the following structure, to provide consistent layout of information across many different projects:

* project-pack/
  * 1--content/
    * word, excell files
  * 2--design/
    * psd / ai / sketch files
  * 3--assets/
    * web-icons.ai
    * icons.ai
    * images/
      * site/
      * content/
* www/

---

## Resources & Templates

The following assets and workflow Google Docs should be quite useful to you:

* [Default Asset Sheet](#) * Font, colors, sizing and spacing information.
* [Default Workflow Sheet](#) * Checklists for various stages in the project lifecycle.
* Default Architecture Sheet * Coming soon

---

## General Guidelines

The following chapters deal with general guidelines when producing content & assets for any given project.

#### Index

* Basic Rules
* Providing Designs
* Providing Content
* Providing Assets

### Basic Rules

* **Spell check** - Please make sure that copy is properly checked & edited. This step alone will save hundreds of dev hours.
* **Document your handover** - Handing over large project work is hard. Follow the process and checklists, and document as much as possible.
* **Consistent naming** - Adopt a consistent naming structure throughout the *entire* project.
* **Give the developer all of the information** - if you don't tell us about a thing, we won't do that thing.

### Providing designs

* Provide open files as well as a rendered version (pdf please!)
* Add versions in your filenames.
* Name your artboards and layers as if a stranger will read them.
* Expand your layers and convert text properly.
* Inform the developer of hidden layers and what they mean.

### Providing content

* Provide content as simply as possible. Markdown is loved, but word docs are also okay.
* Please avoid using excell for content. It's very hard to work with and keep track off.
* *Never* put images in the content document *ever*. Please reference to them with a tag: `[IMAGE: 3--assets/images/content/about.jpg]`

### Providing images

* Group images to a consistent aspect-ratio set, and name them as such.
* Optimise all images as best you can. We run our own automated scripts, but the responsibility lies with you to ensure images are as small as possible while still looking great.
* Organise images into groups and name them consistently.
* Provide icons as a single .ai file with separate, named artboards. This allows us to ensure quality and compression.

#### system-icons.ai

This file contains artboards for the common system icon sizes that are generally required for websites.

You can simply fill them in and save the ai file. We can render out the icons ourselves.

Don't change the artboard names as they contain the required filenames for the icons.

##### Image type rules

Follow these rules explicitly. Deviations will be sent back to creative.

* **JPG** -  For photos and complex images
* **PNG** -  For images that require transparent background. Generally best to keep this format for simpler images
* **SVG** -  For icons, logos and simple illustrations.
