# php-wiki-status-code-plugin

PHP Wiki Status Code Plugin

## Description

A plugin to give a wiki page an alternate http return code.

e.g. `404 Not Found` - when a wiki page has no revisions.

## Example

Placed in a normal wiki page:

<?plugin StatusCode code="404" ?>

this will cause the page to be returned as 404 Not Found.

## Parameters

#### code

The http return code to use.

#### text

The text to return with the code. If this is not present a look up table is used to find the correct text for that error code.
