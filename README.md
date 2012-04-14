# Meteor on dotCloud

To deploy your Meteor application on dotCloud, add the following files to your meteor project:

- dotcloud.yml
- .dotcloudbuilder
- .dotcloudignore

Then use the dotCloud CLI and do ``dotcloud push mymeteorappname``.
One minute later, the URL to your app will be shown!

## Scaling

To scale the database tier, just do e.g. ``dotcloud scale db:instances=3``.
