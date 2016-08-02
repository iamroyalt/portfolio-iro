---
layout: post
title: Bloccit
feature-img: "img/sample_feature_img.png"
thumbnail-path: "https://d13yacurqjgara.cloudfront.net/users/3217/screenshots/2030966/blocjams_1x.png"
short-description: Bloccit is an application similiar to Reddit.

---

Bloccit is a Reddit clone built following Bloc's backend foundation course. This course covered many of the fundamentals of web development such as Git/Github, Command Line, Text Editors, HTML, CSS, Ruby and the Rails framework.

Bloccit is an easy-to-use website that operates as a forum. Once the user has completed the sign-up process, they can begin creating new posts, as well as commenting on existing ones. The user can also favorite a post created by another user, which will allow them to follow any additional comments made vie email alerts. The user is also able to comment on posts, delete their own posts and vote up or vote down other user's posts.

Bloccit's user authentication was handled by using the Devise gem, which streamlined the registration process. The Pundit gem was used to control whic views a user had access to depending on their user type (admin, guest, moderator, member). Bloccit was "Ajaxified" to create a better user experience.
