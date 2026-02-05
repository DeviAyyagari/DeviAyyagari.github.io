---
permalink: /
title: "Kameswari Devi Ayyagari"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! My name is Kameswari Devi Ayyagari. I am a PhD candidate at Dalhousie University applying machine learning to ecological monitoring, with a focus on low-light, deep-sea marine survey video. I build scalable, uncertainty-aware computer vision pipelines to improve population detection and counting. The best way to reach me is by email at *akdevi.92 AT gmail*.

My work addresses limited labeled data, class imbalance, domain shift, and unseen species using coarse-to-fine detection, open-set and uncertainty-aware modeling, and foundation models. I also build practical tools for ecologists, including visualization and human-in-the-loop annotation workflows.

My goal is to bridge modern machine learning with applied ocean science to support more effective, data-driven ecological research and decision-making.

Prior to my PhD, I worked on machine learning for healthcare, including whole-slide image classification and image reconstruction.

Currently I am exploring
- Foundation models in end-to-end ecological monitoring pipelines
- Out-of-distribution detection and self-supervised clustering to reduce annotation burden
- Scalable coarse fish detectors trained on large datasets to support fine-grained classification


# Research Interests
- Marine ecosystem and biodiversity monitoring
- Out-of-distribution and uncertainty-aware modeling
- Machine Learning
- Computer vision

## Publications

{% include publications-table.html %}

## News & Updates

{% include newsupdates-table.html %}

<style>
  .publications-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0 0.85rem;
    font-family: "Crimson Text", "Georgia", serif;
    border: none;
  }

  .publications-table td {
    border: none;
  }

  .pub-label {
    width: 20%;
    color: #7d7d7d;
    font-style: italic;
    font-size: 0.65rem;
    text-align: right;
    vertical-align: middle;
    letter-spacing: 0.04em;
    padding-right: 0.5rem;
  }

  .pub-entry {
    width: 80%;
    color: #1f1f1f;
    vertical-align: top;
    padding-left: 0.5rem;
  }

  .pub-entry-link {
    display: block;
    text-decoration: none !important;
    border-bottom: none !important;
    color: inherit !important;
  }

  .pub-entry-link:hover,
  .pub-entry-link:focus,
  .pub-entry-link:visited {
    text-decoration: none !important;
    border-bottom: none !important;
    color: inherit !important;
  }

  .pub-title {
    font-size: 0.95rem;
    font-weight: 500;
    vertical-align: top;
    margin-bottom: 0.25rem;
    color: #7a7a7a;
  }

  .pub-details {
    font-size: 0.7rem;
    color: #7089a6;
  }

  .pub-link {
    color: #34507c;
    font-weight: 500;
    margin: 0 0.15rem;
  }

  .pub-notes {
    font-size: 0.9rem;
    color: #777;
    margin-top: 0.2rem;
  }

  .news-text {
    font-size: 0.85rem;
    color: #4f5a68;
    line-height: 1.45;
    font-weight: 400;
  }

  @media (max-width: 600px) {
    .publications-table,
    .publications-table tbody,
    .publications-table tr,
    .publications-table td {
      display: block;
      width: 100%;
    }

    .pub-label {
      margin-bottom: 0.15rem;
      letter-spacing: 0.08em;
    }
  }
</style>
