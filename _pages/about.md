---
layout: about
title: about
permalink: /
subtitle: Welcome to my website!

profile:
  align: justified
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Boston University</p>
    <p>Department of Economics</p>
    <p>B30A - 270 Bay State Road</p>
    <p>Boston, MA 02134</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # social icons are placed directly below the contact text instead

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Ph.D. Candidate in Economics at Boston University. I am available for interviews for the 2026-2027 job market.

My interests are in Microeconomic Theory, IO, and Behavioral Economics. My research sits at the intersection of microeconomic theory, industrial organization, and behavioral economics. I study how bounded rationality and social concerns shape the strategic behavior of firms and the rise of social norms.

You can find my CV [here]({{ '/assets/pdf/cv_luis_linhares.pdf' | relative_url }}).

**Fields**: Microeconomic Theory, Decision Theory, Industrial Organization, Behavioral Economics

**You can contact me at**: [lhrlinha@bu.edu](mailto:lhrlinha@bu.edu)

<!-- markdownlint-disable MD033 -->
<style>
  .about-social {
    margin-top: 0.5rem;
    text-align: left;
  }

  .about-social .contact-icons {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 0.5rem;
    font-size: 1.5rem;
  }

  .about-social .contact-icons a {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-width: 2rem;
    min-height: 2rem;
    line-height: 1;
  }

  .about-social .contact-icons a:focus-visible {
    outline: 2px solid var(--global-theme-color);
    outline-offset: 3px;
    border-radius: 0.2rem;
  }

  .about-social .contact-icons a img,
  .about-social .contact-icons a svg {
    width: 1.5rem;
    height: 1.5rem;
    margin-bottom: 0;
  }

  .about-social .contact-icons a svg image {
    width: 1.5rem;
    height: 1.5rem;
  }
</style>

<div class="social about-social" role="group" aria-label="Contact and social links">
  <div class="contact-icons">{% social_links %}</div>
</div>
<!-- markdownlint-enable MD033 -->
