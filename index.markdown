---
layout: default
---
<div class="home">
<div class="full-hero hero-home">
  <div class="hero-content">
  <h1>CODE DANGEROUSLY</h1>
  <ul class="social-list">
    {% include social-link.html %}
  </ul>
  </div>
  </div>
  <div class="home-callout">
  <h1 class="callout-title">The Learn Enough Story</h1>
  <div class="Callout-copy">
  <p>
    Learn Enough to be Dangerous is a leader in the movement to teach the world
    <em>technical sophisticiation</em>, which includes both "hard skills" like
    coding, command lines, and version control, and "soft skills" like guessing
    keyboard shortcuts, Googling error messages, and knowing when to just reboot
    the darn thing.
  </p>
  <p>
    We believe there are <strong> at least a billion people</strong> who can
    benefit from learning technical sophistication, probably more.  To join our
    movement, <a href="https://learnenough.com/#email_list">sign up for our official
    email list</a> now.
  </p>
  <h3 class="home-callout">Background</h3>
  <p>
    Learn Enough to Be Dangerous is an outgrowth of the <a href="https://railstutorial.org/">
    Ruby on Rails Tutorial</a> and the <a href="https://softcover.io/">Softcover publishing platform
    </a>.  This page is part of the sample site for <a href="https://learnenough.com/css-tutorial"><em>
    Learn Enough CSS and Layout to Be Dangerous</em></a>, which teaches the basics of <strong>C</strong>
    ascading <strong>S</strong>tyle <strong>S</strong>heets, the language that alllows web pages to be
    styled.  Other related tutorials can be found at <a href="https://learnenough.com/">learnenough.com</a>.
  </p>
  </div>
</div>
<div class="home-section">
<h4>Most recent post</h4>
<div class="blog-posts">
<header class="post-header">
<h2>
<a href="{{site.posts.first.url}}">
{{site.posts.first.title}}</a>
</h2>
<div class="post-byline">
<img src="{{site.posts.first.gravatar}}">
<a href="{{site.posts.first.authorTwitter}}" class="social-link">Tw</a>
by: {{site.posts.first.author}}
<span>- {{site.posts.first.date | date: '%B %d, %Y'}}</span>
</div>
</header>
<div class="posts-image"
style="background-image:ulr({{site.posts.first.postHero}})"></div>
{{site.posts.first.excerpt}}
</div>
</div>
<div classs="home-section">
  <h2>THE FOUNDERS</h2>
  <p>
    Learn Enough to Be Dangerous was founded in 2015 by Michael Hartl, Lee
    Donahue, and Nick Merwin.  We believe that the kind of technical sophistication
    taught by the Learn Enought utorials can benefit at least a billion people,
    and probably more.
  </p>
</div>

<div class="bio-wrapper">
  <div class="bio-box">
    <img src="https://placekitten.com/g/400/400">
    <h3>Michael Hartl</h3>
    <a href="https://twitter.com/mhartl" class="social-link">Tw</a>
    <div class="bio-copy">
    <p>
      Known for his dazzling charm, rapier wit, and unrivaled humility,
      Michael is the creator of the
      <a href="https://railstutorial.org">Ruby on Rails Tutorial</a> and
      principal author of the <a href="https://learnenough.com">Learn Enough to
      Be Dangerous</a> introductory sequence.  Michael is also notorious as the
      founder of <a href="http://tauday.com">Tau Day</a> and author of
      <a href="http://tauday.com/tau-manifesto"><em>The Tau Manifesto</em></a>,
      but rumors that he's secretly a supervillain are slightly exaggerated.
    </p>
    </div>
  </div>
  <div class="bio-box">
    <img src="https://placekitten.com/g/400/400">
    <h3>Lee Donahue</h3>
    <a href="https://twitter.com/leedonahue" class="social-link">Tw</a>
    <div class="bio-copy">
    <p>
      When he's not literally swimming with sharks or hunting powder stashes on
      his snowboard, you can find Lee in front of his computer designing interfaces,
      doing front-end development, or writting some of the interface-related
      Learn Enough tutorials.
    </p>
    </div>
  </div>
  <div class="bio-box">
    <img src="https://placekitten.com/g/400/400">
    <h3>Nick Merwin</h3>
    <a href="https://twitter.com/nickmerwin" class="social-link">Tw</a>
    <div class="bio-copy">
    <p>
      You may have seen him shredding guitar live with Capital Cities on Jimmy
      Kimmel, Conan, or The Ellen Show, but rest assured Nick is a true nerd at
      heart.  He's just as happy shredding well-spec'd lines of code from a tour
      bus as he is from his kitchen table.
    </p>
    </div>
  </div>
  <div class="bio-box">
    <img src="https://en.gravatar.com/userimage/212776763/f16a433db787a95834544826a07ade67.jpg?size=200/g/400/400">
    <h3>Andrea Efthyvoulou</h3>
    <a href="https://twitter.com/the_isabad" class="social-link">Tw</a>
    <div class="bio-copy">
    <p>
      She created this fine page here.  She is an IT Pro.  She loves learning new things
      and has called herself the dark mistress of Excel at times.  In her free time she
      loves learning coding and all things related to IT.
    </p>
    </div>
  </div>
</div>
</div>
