# Create CI

## Install

Copy Files to CustomSpace as per your structure.
Suggested structure  is

- CustomSpace
    - CustomCode
        - CustomCI
            - CustomCI.js

Copy the script loader line into custom.js

If you are not sure how to use script loader, check out this [blog](https://cireson.com/blog/how-to-organize-your-customspace-with-a-script-loader/ "Script Loader Blog")

## Use

Update the ciClasses array on line 10 to contain all the classed you want to create.
For each CI type you want to be able to create, you need to add:

1. Display Name (this doesn't have to match the actual class definition)
1. ClassId (retrieve this via PowerShell)
1. Icon (any Font Awesome icon up to version 4.2. Full list [here](https://astronautweb.co/snippet/font-awesome-icons-v4-2/ "Font Awesome 4.2 Icons"))

The functionality will be available to Analysts. If you need this changed, update line 6.

Then you can create CIs from the NEW drawer.

## Please Note

Due to a limitation of the Cireson Portal, the Create CI works differently to Creating any other type of object. Upon clicking the type you want to create, an empty object is created AND committed to the database. The Portal will then redirect you to edit that object. If you navigate away from this page, the empty object will still exist.

## Contributors

All contribution welcome.
