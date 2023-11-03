---
title_tag: Next Steps | Google Cloud
meta_desc: This page provides a list of tutorials that take a deeper dive into
            Google Cloud cloud resources.
title: Next steps
h1: "Pulumi & Google Cloud: Next steps"
weight: 9
menu:
  clouds:
    parent: google-cloud-get-started
    identifier: gcp-next-steps

aliases:
- /docs/quickstart/gcp/next-steps/
- /docs/get-started/gcp/next-steps/
---

Congrats! You've deployed your first project on Google Cloud with Pulumi. Here are some next steps, depending on your learning style.

## Learn Pulumi

Dive into Learn Pulumi for a comprehensive walkthrough of key Pulumi concepts in the context of a real-life application.

{{< get-started-next-step path="/learn/pulumi-fundamentals" label="Learn Pulumi Fundamentals" ref="gs-gcp-learn" >}}

## Explore Some Examples

Explore our how-to guides for examples of specific architectures or application stacks. These guides are available in all Pulumi languages and cover many common architectures such as [GKE clusters](/registry/packages/gcp/how-to-guides/gcp-ts-gke-hello-world/), [Cloud Run containers](/registry/packages/gcp/how-to-guides/gcp-ts-cloudrun/), and [Cloud Function HTTP endpoints](/registry/packages/gcp/how-to-guides/gcp-ts-functions/).

{{< get-started-next-step path="/registry/packages/gcp/how-to-guides" label="Explore How-to Guides" ref="gs-gcp-guides" >}}

## Learn How Pulumi Works

Learn how Pulumi works from its architecture to key concepts, including [stacks](/docs/concepts/stack/), [state](/docs/concepts/state/), [configuration](/docs/concepts/config/), and [secrets](/docs/concepts/secrets/).

{{< get-started-next-step path="/docs/concepts/" label="Read Documentation" ref="gs-gcp-docs" >}}

## Try Pulumi ESC (Environments, Secrets, and Configuration)

In this guide, you configured a single Pulumi program for Azure using [stack configuration](/docs/concepts/config/) and environment variables. Did you know you can apply the same configuration settings across multiple Pulumi projects (and even other applications) with [Pulumi ESC](/product/esc/)?

Currently in public preview, Pulumi ESC introduces the concept of _environments_ --- managed collections of static and dynamic configuration that you can use to manage any Pulumi project or application, including with short-lived credentials through OpenID Connect.

{{< get-started-next-step path="/blog/environments-secrets-configurations-management/" label="Learn more about Pulumi ESC" ref="gs-azure-esc" >}}

## Check Out the Blog

Read through the latest blog posts about using Pulumi with Google Cloud, including everything from new Google Cloud features and products supported by Pulumi to technical architectures and best practices.

{{< get-started-next-step path="/blog/tag/google-cloud" label="Read the Pulumi Blog" ref="gs-gcp-blog" >}}
