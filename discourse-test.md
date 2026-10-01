---
title: "Discussion Test"
layout: single
permalink: /discourse-test/
comments: false
---

This page is testing the full interactive Discourse discussion.

<div id="discourse-comments"></div>

<script type="text/javascript">
  window.DiscourseEmbed = {
    discourseUrl: 'https://chinesehandwriting.discourse.group/',
    topicId: 9,
    fullApp: true,
    dynamicHeight: true,
    embedMinHeight: '500',
    embedMaxHeight: '900',
    embedHeight: '600px'
  };

  (function() {
    var d = document.createElement('script');
    d.type = 'text/javascript';
    d.async = true;
    d.src = window.DiscourseEmbed.discourseUrl + 'javascripts/embed.js';
    (document.getElementsByTagName('head')[0] ||
     document.getElementsByTagName('body')[0]).appendChild(d);
  })();
</script>
