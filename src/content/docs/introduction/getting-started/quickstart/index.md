---
section: getting-started
title: Quickstart
---

<script lang="ts">
  import PopularQuickstart from "$lib/components/docs/quickstart/popular-quickstart.svelte";
  import QuickstartSearch from "$lib/components/docs/quickstart/quickstart-search.svelte";
  import OpenGraph from "$lib/components/open-graph.svelte";
</script>

<OpenGraph
data={{
    description:
      "Learn how to start using Gitpod on an example project/template that is hosted on GitHub in less than 5 minutes. Get up and running with Gitpod quickly.",
    title: "Quickstart - Gitpod",
    keywords: "template, get started, example",
  }}
/>

# Quickstart

Learn how to start using Gitpod on an example project that is hosted on GitHub in less than 5 minutes. For simplicity we use GitHub as the git hoster but the steps outlined work equally well for GitLab and Bitbucket. This section helps you understand the features and advantages of Gitpod in a learning environment. All templates are pre-configured to use Gitpod and ready-to-code:

## Templates

### Popular Templates

<PopularQuickstart />

### Find your template

<QuickstartSearch />

<br>

💡 Find more such templates on [Gitpod Samples](https://github.com/gitpod-samples)

## Installing the Gitpod browser extension

You can install the Gitpod browser extension in any [Chromium-based](https://chrome.google.com/webstore/detail/gitpod-online-ide/dodmmooeoklaejobgleioelladacbeki) browser such as Google Chrome, Microsoft Edge, Brave, and others, or in [Firefox](https://addons.mozilla.org/firefox/addon/gitpod/).

The Gitpod extension adds a Gitpod button on every project and branch across GitLab, GitHub, and Bitbucket so that you can easily open a new workspace for any project.

![Browser Extension](/images/docs/browser-extension-lense.png)

If you prefer to not install browser extensions then you can use the Gitpod [browser bookmarklet](/docs/configure/user-settings/browser-bookmarklet) instead.

## Next Steps

With Gitpod you start treating your dev environments as something ephemeral: you start them, you code, you push your code, and you forget about them. For your next task, you'll use a fresh dev environment.

-   [Getting started with your own project](/docs/introduction/getting-started)
