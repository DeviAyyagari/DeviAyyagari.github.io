---
permalink: /
title: "Kameswari Devi Ayyagari"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! My name is Kameswari Devi Ayyagari. I am interested in studying and leveraging machine learning algorithms to advance biology, medicine and healthcare. The best way to reach me is by email at *akdevi.92 AT gmail*.

I am a PhD candidate at Dalhousie University specializing in the development and application of machine learning methods for ecological and environmental monitoring. My doctoral research focuses on designing scalable, uncertainty-aware computer vision pipelines for analyzing low-light, deep-sea underwater video collected during marine surveys, with the goal of improving how marine populations are detected, counted, and monitored over time.

My work addresses key challenges inherent to real-world underwater monitoring, including limited labeled data, strong class imbalance, domain and semantic shift across surveys, and the presence of previously unseen species. To tackle these challenges, I develop methods that combine coarse- and fine-grained detection, open-set and uncertainty-aware modeling, and the use of foundation models to improve generalization across deployments, habitats, and years. A central component of my PhD is validating AI-derived population estimates against expert manual counts to ensure methodological advances translate into reliable ecological inference.

In addition to methodological contributions, I build practical tools and workflows to support domain experts. This includes visualization systems for survey data, human-in-the-loop annotation tools that reduce labeling effort, and end-to-end pipelines that integrate detection, counting, and reporting across multiple surveys. This work involves close collaboration with ecologists and practitioners and extensive experience working with large, heterogeneous datasets.

More broadly, my research is motivated by the need for reliable and scalable monitoring to understand how marine ecosystems are responding to climate change. Effective monitoring is a necessary first step for ecological understanding and data-informed management. My goal is to bridge modern machine learning with applied ocean science to support more effective, data-driven ecological research and decision-making.

Prior to my PhD, I worked on machine learning applications in healthcare, including deep learning methods for whole-slide image classification and image reconstruction.

Currently I am exploring
- Leveraging foundation models within end-to-end ecological monitoring pipelines
- Using out-of-distribution detection and self-supervised clustering to reduce annotation burden
- Building scalable coarse fish detectors trained on large datasets to support fine-grained classification
- Developing tools intuitive to ecologists to enable them to use trained models and interpret model outputs


# Research Interests
- Machine Learning
- Computer vision
- Marine ecosystem and biodiversity monitoring
- Out-of-distribution and uncertainty-aware modeling

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
