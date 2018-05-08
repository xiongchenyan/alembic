---
<<<<<<< HEAD
title: CALL FOR PARTICIPATION
feature_text: | 
  ### KG4IR The Second Workshop on Knowledge Graphs and Semantics for Text Retrieval, Analysis, and Understanding 
  held in conjunction with ACM SIGIR 2018, Ann Arbour, MI, USA, July 12, 2018
feature_image: "/pic/theme.jpg"
image: "/pic.theme.jpg"
=======
title: About Alembic
feature_text: |
  ## Alembic
  A Jekyll boilerplate theme designed to be a starting point for any Jekyll website
feature_image: "https://picsum.photos/1300/400?image=989"
excerpt: "Alembic is a starting point for [Jekyll](https://jekyllrb.com/) projects. Rather than starting from scratch, this boilerplate is designed to get the ball rolling immediately. Install it, configure it, tweak it, push it."
>>>>>>> daviddarnes/master
---

Semantic technologies such as controlled vocabularies, thesauri, and knowledge graphs have been used throughout the history of information retrieval for a variety of tasks. Recent advances in knowledge acquisition, alignment, and utilization have given rise to a body of new approaches for utilizing knowledge graphs in text retrieval tasks. 

<<<<<<< HEAD
This workshop focuses on the end-to-end utilization of knowledge graphs and semantics in text retrieval, text understanding and other IR-related applications. Its scope covers the acquisition, the alignment, and the utilization of knowledge graphs and semantic resources for the purpose of optimizing end-to-end performance of a system that responds to a user's information need. Examples of such technologies and applications include entity ranking, entity linking, entity-based retrieval models, entity recommendation, document filtering, knowledge graph population, and more. 
=======
{% include button.html text="Fork it" icon="github" link="https://github.com/daviddarnes/alembic" color="#0366d6" %} {% include button.html text="Tweet it" icon="twitter" link="https://twitter.com/intent/tweet/?url=https://alembic.darn.es&text=Alembic%20-%20A%20Jekyll%20boilerplate%20theme&via=DavidDarnes" color="#0d94e7" %} {% include button.html text="Install Alembic ⚗️" link="https://github.com/daviddarnes/alembic#installation" %} {% include button.html text="Tip me $5 💸" link="https://www.paypal.me/daviddarnes/5usd" color="#333333" %}
>>>>>>> daviddarnes/master

The goal of the KG4IR workshop is to consolidate the community efforts and study how such technologies can be employed in information retrieval systems in the most effective way. We are calling for papers on ongoing research and position papers as well as talk abstracts for future trends, tasks, and open problems to ensure that breakthroughs, and, technologies algorithms in this space are widely disseminated. We are particularly interested in practical experiences with KG technology both from academia and industry.

<<<<<<< HEAD
=======
- Available as a **theme gem** and **GitHub Pages** theme
- Simple and elegant design that can be used out of the box or as solid starting point
- Tested in all major browsers, including **IE and Edge**
- Built in **Service Worker** so it can work offline and on slow connections
- **Configurable colours** and typography in a single settings file
- Extensive set of **shortcodes** to include various elements; such as buttons, icons, figure images and more
- Solid **typographic framework** from [Sassline](https://sassline.com/)
- Configurable navigation via a single file
- Modular Jekyll components
- Post category support in the form of a single post index page grouped by category
- Built in live search using JavaScript
- **Contact form** built in using [Formspree](https://formspree.io/)
- Designed with **[Siteleaf](http://www.siteleaf.com/)** in mind
- Has 9 of the most popular networks as performant sharing buttons
- Has documentation
>>>>>>> daviddarnes/master

Topics of this workshop include but are not limited to:

* Acquisition for IR applications
  - knowledge graph population and semantic resource construction for IR
  - domain/task-specific knowledge graph construction
  - knowledge representation for IR
  - query-time knowledge extraction

<<<<<<< HEAD
=======
- [bitpodcast.com](https://bitpodcast.com/)
- [joelcagedesign.com](https://joelcagedesign.com/)
- [bawejakunal.github.io](https://bawejakunal.github.io/)
- [case2111.github.io](http://case2111.github.io/)
- [www.10people.co.uk](http://www.10people.co.uk/)
- [hrkeni.me](http://hrkeni.me/)
- [ccs17.bsc.es](https://ccs17.bsc.es/)
- [karateca.org](http://www.karateca.org/)
>>>>>>> daviddarnes/master

* Alignment with and for queries
  - entity linking for short queries and documents
  - relation extraction for query and document modeling
  - information integration and ontology matching
  - entity search
  - knowledge subgraph selection

<<<<<<< HEAD

* Utilization for text retrieval
  - ad hoc document and passage retrieval
  - understanding user queries
  - question answering
  - dialogue systems and conversational search
  - event tracking and summarization
  - knowledge-focused diversification and summarization of SERPs
  - tracking of events
  - complex answer retrieval


Dual Submission to the KG4IR Special Issue at the Information Retrieval Journal
-------------------------------------------------------------------------------

Authors planning a submission to the KG4IR Special Issue in the Information Retrieval Journal, we offer the opportunity to simultaneously submit a talk abstract to the KG4IR workshop. In this case, please indicate the paper title of the journal submission when submitting the talk abstract.


[Special Issue Call for Papers](https://kg4ir.github.io/cfp/CfP_SI_kg4ir.pdf)



[Paper Submission](/submit)

[Important Dates](/dates)

=======
### As a Jekyll theme

1. Add `gem "alembic-jekyll-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the theme and its dependancies
3. Add `theme: alembic-jekyll-theme` to your `_config.yml` file to set the site theme
4. Run `bundle exec jekyll serve` to build and serve your site
5. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a GitHub Pages remote theme

1. Add `gem "jekyll-remote-theme"` to your `Gemfile` to add the theme as a dependancy
2. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
3. Add `jekyll-remote-theme` to the list of `plugins` in your `_config.yml` file
4. Add `remote_theme: daviddarnes/alembic` to your `_config.yml` file to set the site theme
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

### As a Boilerplate / Fork

_(deprecated, not recommended)_

1. [Fork the repo](https://github.com/daviddarnes/alembic#fork-destination-box)
2. Replace the `Gemfile` with one stating all the gems used in your project
3. Delete the following unnecessary files/folders: `.github`, `LICENSE`, `screenshot.png`, `CNAME` and `alembic-jekyll-theme.gemspec`
4. Run the command `bundle install` in the root of project to install the jekyll remote theme gem as a dependancy
5. Run `bundle exec jekyll serve` to build and serve your site
6. Done! Use the [configuration](#configuration) documentation and the example [`_config.yml`](https://github.com/daviddarnes/alembic/blob/master/_config.yml) file to set things like the navigation, contact form and social sharing buttons

## Customising

When using Alembic as a theme means you can take advantage of the file overriding method. This allows you to overwrite any file in this theme with your own custom file, simply by matching the file name and path. The most common example of this would be if you want to add your own styles or change the core style settings.

To add your own styles copy the [`styles.scss`](https://github.com/daviddarnes/alembic/blob/master/assets/styles.scss) into your own project with the same file path (`assets/styles.scss`). From there you can add your own styles, you can even optionally ignore the theme styles by removing the `@import "alembic";` line.

If you're just looking to set your own colours and fonts copy the [`_settings.scss`](https://github.com/daviddarnes/alembic/blob/master/_sass/_settings.scss) file into your project at the same file path (`_sass/_settings.scss`) and change variables however you wish. The settings are a mixture of custom variables and settings from [Sassline](https://medium.com/@jakegiltsoff/sassline-v2-0-e424b2881e7e) - follow the link to find out how to configure the typographic settings.
>>>>>>> daviddarnes/master
