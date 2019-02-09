# EXIFStripper
Strips EXIF Data from Images

Uses blocking toDataURL, so if you take a full res JPG image, convert it to PNG, it will use a ton of RAM and potentially crash your browser.

It's pretty darn beta.


Powers http://exifstripper.com

## Goals:
 - Do not leverage external libraries.
 - The application should be a self-contained single page application. A user should be able to "Save as" the page, and run it locally without an internet connection.
 
The goals here are to ensure that users of this page have no concerns about their images, EXIF data, or other data being sent to a server.
