# 3. Have base set of stories and scrape diff periodically

Date: 2019-02-18

## Status

Accepted

## Context

The project mainly concentrated around working with StoryWeaver's stories.
The stories are added on a regular basis. Stories can also be unpublished either for updating or romoved permanantly.

## Decision

The dataset would contain a baseset of stories. Every month we would collect the difference in stories from the platform under 3 categories: 1. New Stories
2. Updated Stories
3. Deleted Stories

## Consequences

Eventually the data pipeline would automatically updated on peiodic basis to create the current state of stories which would be updated to the MT models.