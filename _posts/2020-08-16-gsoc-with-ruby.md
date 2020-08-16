---
layout: post
title: GSoC with Ruby
subtitle: Working on rubygems.org for summer '20
gh-repo: vachhanihpavan/rubygems.org
gh-badge: [star, fork, follow]
tags: [gsoc, ruby, rubygems.org]
---

Hi, everyone! This blog post will be about my journey of getting into Google Summer of Code program.
I learned Ruby on Rails in my second year of bachelors degree@NITK and 
have been continuously learning since then. I worked on a Management Information System
of my university, called IRIS for over two years which was built on Rails.
After being lazy(and a little scared 👻) to apply for GSoC'19, I made a proposal
for a project on rubygems.org in Ruby organisation. 

### Application

I made a proposal for only one [project](http://rubygsoc.github.io/add-gem-owner-add-and-remove-in-web-ui-of-rubygems.org/) which involved adding new features to rubygems.org.
I got in touch with [sonalkr132](https://github.com/sonalkr132), the mentor for the project and he suggested me get involved with the community and try to send some PRs to open issues.
On his suggestion, I worked on following issues:
 - [Show yanked gem in search filters](https://github.com/rubygems/rubygems.org/pull/2339)
 - [Added route to redirect /users to /profile](https://github.com/rubygems/rubygems.org/pull/2264)

For my proposal to the project, I worked in writing a RFC explaining the need for the project
, detailed flow and design.
 
Finally, on 4th May, 2020 I got the acceptance mail 🎉.
![Acceptance](/assets/img/2020-08-16/acceptance.png)


### Project

My project on rubygems.org was to add feature for adding/remove gem owners via UI
as an alternative to `gem owner -a/r` via CLI. The next part of the project was 
to implement a new flow for ownership transfers where maintainers of the gem can
look for co-maintainers or new maintainers and smoothly transfer ownership.

There had been discussions about taking over maintenance of gems, transferring ownerships of gems
whose maintainers are not active anymore and make those namespaces available to interested developers.
A lot of discussion around this idea by [Benjamin Fleishcher](http://www.benjaminfleischer.com/2014/08/17/rubygems-adoption-center/) and some related work is here:

- [Rubygems Adoption Center](https://github.com/rubygems/adoption-center)
- [Gem Adoption](https://github.com/rubygems/rubygems.org/pull/1842)

My work on this project will be a step towards easing the process of 
ownership transfer for the maintainers of the gems.

More details about the project:
 - [Project Page](http://rubygsoc.github.io/add-gem-owner-add-and-remove-in-web-ui-of-rubygems.org/).
 - [Link to RFC](https://github.com/rubygems/rfcs/pull/25/)

Thank you!
