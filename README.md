# Coding to Learn and Create

The repository for the [Coding to Learn and Create](https://codelearncreate.org/) website. This site is managed using [Hugo](https://wiki.fluidproject.org/display/fluid/Maintain+Websites+Using+Hugo) and deployed using [Cloudflare Pages](https://dash.cloudflare.com/ac36c95f6ffa664eda33df48aa43c298/pages/view/codelearncreate-org).

## Develop Locally

You will need to [install Hugo](https://gohugo.io/getting-started/installing/) and then run this command in the root of this directory:

```
hugo server
```

Now visit http://localhost:1313/ to preview any changes you're making.

## Add Blog Posts

To add a new blog post:

* Create a subdirectory in the [blog](https://github.com/codelearncreate/c2lc-website/tree/master/content/blog) directory
* Optionally create an ``images`` directory in the new subdirectory
* Create an ``index.md`` file for the content -- refer to files from [previous posts](https://github.com/codelearncreate/c2lc-website/tree/master/content/blog) for examples of required layout

## Deploy Changes

Pushing changes to the ``master`` branch of this repository will trigger deployments. Generally it will take a couple minutes before changes are reflected on the [live site](https://codelearncreate.org/).
