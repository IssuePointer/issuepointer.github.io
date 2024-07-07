---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  # overlay_image: /assets/images/unsplash-image-1.jpg
  actions:
    - label: "Watch the demo"
      url: "https://www.youtube.com/watch?v=yxJYfusxtaI"
    - label: "Read the manual"
      url: "https://wiki.issuepointer.com/en/manual"
excerpt: "IssuePointer optimizes bug resolution in large projects by identifying similar past issues, guiding new developers via bug localization, and refining predictions based on feedback."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'

feature_row:
  - image_path: /assets/gh_zoomed.png
    alt: "placeholder image 1"
    image_caption: IssuePointer GitHub app
    title: "Similar Issue Detection"
    excerpt: "Provides developers with 10 most similar issues to the issue at hand."
  - image_path: /assets/vscode.png
    image_caption: "IssuePointer VSCode Extension"
    alt: "placeholder image 2"
    title: "Bug Localization"
    excerpt: "Give developers a starting point for debugging the issues by suggesting suspected files."
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
  - image_path: /assets/analytics.png
    title: "Analytics"
    excerpt: "Provide insights on IssuePointer usage, and manage your repositories and developers."
feature_row2:
-   title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    # url: "#test-link"
    # btn_label: "Read More"
    # btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
<!-- # IssuePointer -->
<!-- <center>
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/yxJYfusxtaI?si=Bka9mJ1H1HJlrzq9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</center> -->



{% include feature_row %}

## Why IssuePointer?
- **Combines similar issue detection and bug localization into a coherent experience.** IssuePointer helps developers tackling bugs and regressions in complex software projects by providing them points of comparison (similar issues) and a jumping point for debugging (file-level bug localization).  
- **Designed for on-premises deployment first.** We provide companies using IssuePointer with a `company.issuepointer.com` subdomain and container images of our software. Our customers are free to deploy IssuePointer on company premises or on existing cloud platforms. IssuePointer works wherever docker is available.
- **Private and secure.** IssuePointer *doesn't rely on external LLMs*, so your data never leaves your company servers. All communication between the model and GitHub is encrypted by keys provided by the customer, ensuring that neither third parties nor the IssuePointer team can read their data without consent.
- **Seamless integration with existing tools.** IssuePointer integrates with GitHub and Visual Studio Code so that the developers don't have to learn how to navigate yet another user interface. The UI elements of our VSCode extension can be customized to the individual developer's liking. 

<!-- {% include feature_row id="feature_row2" type="left" %} -->
<!-- 
{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %} -->

## Project Description

The scope of the project is to aid developers in resolving bug reports by finding similar issues and pointing the developers towards possible solutions. This project scans the source code and extract data from bug reports to find similar issues in the past if they exist, find code segments that are suspected to introduce the problem in a given bug report, and possibly suggest solutions based on past issues and their solutions. The project will be implemented as an extension for the Visual Studio Code IDE and GitHub issues.

## Documentation
* [IssuePointer User Manual](https://wiki.issuepointer.com/en/manual)

<!--
## Team Members
* Alphan Eker
* Berkan Şahin
* Efe Yakar
* Serdar Özata
* Şeymanur Kılıç

## Project Reports
* [Specification Documents](./docs.html)
* [Analysis and Requirements Report](./docs.html)
-->
