PyroCMS-Multiple-Images-FieldType
=================================

Add multiple images to your streams using a very nice html5 file uploader [plupload](http://www.plupload.com/) version 1.5.7


Team
===========================

[Jose Luis Fonseca](http://josefonseca.me)

[Rigo B Castro](http://twitter.com/rigobcastro)


Installation
===========================

1. Download the zip package
2. Create a folder under addons/shared_addons/field_types/ and name it multiple_images
3. Copy and paste the zip content.

That's it!


Usage
===========================

Drop or select images from your PC, they will be uploaded and related to the entry, once you are ready to use them in your front end do 

	{{field_slug}}
		{{img}}
	{{/field_slug}}


Properties
===========================

The field type has the following properties when you set it up:

<b>Images Folder:</b> Since it uses the files module, you must select a folder to upload the images

<b>Max Images:</b> By default it will be 5, you can change this to the number of images you want to limit.

