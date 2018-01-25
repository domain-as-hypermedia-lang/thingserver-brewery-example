# Thingserver Brewery Example

## Status

Draft.

## About

Illustrates the structure of a domain on disk ready to be served out by
Thingserver.

## Structure

The domain resources are organised as a flat set so they can be assembled into
any number of graphs (user journeys).

There is a minimum of at least 1 media type (default) and any number of
(simplified here as something we append on after a hyphen to the resource name).

For every resource/media type pair we have a doc (md) and schema file.

We assume here that our media types will not be the experimental variety but
rather of the more publishable form: application/vnd.thingserver.brewery+json.

We assume also that versions of the public (external contract) form are
undesirable for the obvious reasons - so these will not be part of either our
URIs or the media types.
