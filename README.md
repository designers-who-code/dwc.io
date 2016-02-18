#Designers Who Code Website

dwc.io is a Jekyll based website hosted on AWS S3. It uses a custom `_events` post type to manage all event pages, and otherwise is pretty vanilla.

Requirements
* node
* npm

##Deploys

Deployments are automated using a [jekyll-hook](https://github.com/developmentseed/jekyll-hook) (hook is currently setup on one of Robert Nealan's servers). Any time there is a push or merge to `master` the hook will automatically pull in the latest version of `master`, build the site, and deploy live to S3. If you're not ready to deploy something then keep it on a branch.

##Contributing

If you're interested in helping out with the website or the group, feel free to ping us on ~~Slack~~ (soon) or email us at info@dwc.io. Any non-core member contributors should put in a Pull Request, which we'll gladly review and discuss as needed.

=====

More to come soon.