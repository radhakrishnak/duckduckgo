# Welcome to DuckDuckHack!

[DuckDuckHack](http://duckduckhack.com/) is an open source platform built by [DuckDuckGo](https://duckduckgo.com) and its community members to provide a better DuckDuckGo search experience with, "instant answers."

Instant answers provide highly useful information (like the [solution to an equation](https://duckduckgo.com/?q=multiples+of+42) or a snippet of [biographical information](https://duckduckgo.com/?q=neil+degrasse+tyson)) to searches performed on DuckDuckGo. For some of our favorite examples, check out: 

- [Twitter information](https://duckduckgo.com/?q=%40duckduckgo)
- [Live flight status](https://duckduckgo.com/?q=aa+102)
- [Recipes by ingredient](https://duckduckgo.com/?q=tofu+ginger)

Instant answers are displayed at the top of the page, above the traditional organic links and our sponsored link, so users can quickly locate the information being provided.

This is an exmaple of an instant answer:
![instant answer example](https://raw.github.com/duckduckgo/DuckDuckGo-Documentation/master/DuckDuckHack/Assets/in_theaters_example.png)

## Getting Involved
Whether you can code or not, there are many ways you can contribute to DuckDuckGo to make a better search experience for everyone:

#### Non-coders can...
- Suggest ideas for instant answers
  Every search can be answered with one perfect result or, "instant answer." Most of our instant answers were suggested by community members, like you, who thought that things like a [password generator](https://duckduckgo.com/?q=password+15) and [currency conversions](https://duckduckgo.com/?q=5+USD+in+GBP) should be answered instantly. We'd love to hear your ideas and you can even help developers around the world bring your instant answer ideas to life.

- Propose source suggestions for current ideas
  Instant answers need source suggestions. For example, our community believes that Rotten Tomatoes is a good source for [movie ratings](https://duckduckgo.com/?q=despicable+me+2+rating). If you know of the best source for a particular interest, please suggest it! 

- Discuss instant answers with others
  Our community thrives on discussion (and debate). We'd love for you to lend your voice to our community so that we can improve DuckDuckGo according to everyone's interests. 

#### Coders can...
- Develop instant answers
  - Continue reading below for our developers guide to creating an instant answer

- Improve current instant answers
  - Help fix current issues or discuss with the community how to make our instant answers better. 

<!-- - If **you are a developer**, please continue reading below to get started with creating your own instant answer! If you here to submit a bug, please make an issue in the correct repository or if you're unsure about which repository is appropriate, please refer to our [Feedback Page](#) (Coming Soon!)

- If **you are not developer**, there is still a lot you can do at our [community website](https://duck.co) and our [ideas companion site](http://ideas.duckduckhack.com/) where you can suggest and comment on instant answer ideas, such as identifying the best websites and data sources to draw from. Contributions of this sort are still very valuable to us and will help direct community efforts. -->

The DuckDuckHack platform is constantly changing as community contributors add new features. We will be improving the platform based on [your feedback](https://www.listbox.com/subscribe/?list_id=197814). Our long-term goal is to be able to distribute all DuckDuckHack (and internal) instant answers via the [DuckDuckGo Instant Answers API](https://api.duckduckgo.com).

* To learn about new plugins, follow [@duckduckhack](https://twitter.com/duckduckhack)
* For ongoing discussion, join the [DuckDuckHack list](https://www.listbox.com/subscribe/?list_id=197814)

## Next Steps

To get started with creating an instant answer, please read the [DuckDuckHack Vision](documentation/duckduckhack_vision.md). This will explain in more detail what the goal and purpose of DuckDuckHack is, as well as explain how to make an excellent instant answer.

## DuckDuckHack Documentation Index

- [For non-coders](documentation/faq.md#what-if-im-not-a-coder-at-all)
- [Why should I make plugins?](documentation/faq.md#why-should-i-make-plugins)
- [DuckDuckHack Vision](documentation/duckduckhack_vision.md)
- [Instant Answer Design Style Guide](https://github.com/duckduckgo/DuckDuckGo-Documentation/blob/master/DuckDuckHack/Styleguide/design_styleguide.md)
  - [Goodie Style Guide](https://github.com/duckduckgo/DuckDuckGo-Documentation/blob/master/DuckDuckHack/Styleguide/Plugin-Specific-Design-Style-Guide/goodie_styleguide.md)
  - [Spice Style Guide](https://github.com/duckduckgo/DuckDuckGo-Documentation/blob/master/DuckDuckHack/Styleguide/Plugin-Specific-Design-Style-Guide/spice_styleguide.md)
  - [Fathead Style Guide](https://github.com/duckduckgo/DuckDuckGo-Documentation/blob/master/DuckDuckHack/Styleguide/Plugin-Specific-Design-Style-Guide/fathead_styleguide.md)
  - [Longtail Style Guide](https://github.com/duckduckgo/DuckDuckGo-Documentation/blob/master/DuckDuckHack/Styleguide/Plugin-Specific-Design-Style-Guide/longtail_styleguide.md)
- [Getting Started](documentation/getting_started.md)
  - [Determining Instant Answer Plugin Type](documentation/getting_started.md#determining-plugin-type)
- [Goodies Walkthrough](documentation/goodies_overview.md)
- [Spice Walkthrough](documentation/spice_overview.md)
- [Fathead Overview](https://github.com/duckduckgo/zeroclickinfo-fathead)
- [Longtail Overview](https://github.com/duckduckgo/zeroclickinfo-longtail)
- [General](documentation/general.md)
  - [Basic Tutorial](documentation/general.md#basic-tutorial)
  - [Triggers](documentation/general.md#triggers)
- [Testing](documentation/testing.md)
  - [Testing Triggers](documentation/testing.md#testing-triggers)
      - [Installing DuckPAN](documentation/testing.md#testing-triggers)
  - [Plugin Test Files](documentation/testing.md#plugin-test-files)
  - [Testing Spice HTML](documentation/testing.md#testing-spice-html)
- [Spice](documentation/spice.md)
  - [Spice Handle Functions (spice backend)](documentation/spice.md#spice-handle-functions)
  - [Frontend Spice development](documentation/spice2.md)
  - [Advanced Spice Backend](https://github.com/duckduckgo/zeroclickinfo-spice#advanced-spice)
- [Location API](documentation/location_api.md)
- [FAQ](documentation/faq.md)
