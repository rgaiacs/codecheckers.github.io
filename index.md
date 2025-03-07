---
layout: page
head_inline: |
   <script type="text/javascript" src="/assets/js/jquery.min.js"></script><!-- https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js -->
   <script type="text/javascript" src="/assets/js/mustache.min.js"></script><!-- https://cdnjs.cloudflare.com/ajax/libs/mustache.js/4.0.1/mustache.min.js -->
   <script type="text/javascript" src="/assets/js/jquery-dateformat.min.js"></script><!-- https://raw.githubusercontent.com/phstc/jquery-dateFormat/master/dist/jquery-dateformat.min.js -->
   <script type="text/javascript" src="/assets/codecheck.js"></script>
---

<div class="row banner">
   <div class="col-6 col-lg">
      <img src="img/codecheck_logo.svg" width="100%" alt="CODECHECK logo" />
      <p class="text-secondary text-justify"><em>Independent execution of computations underlying research articles.</em></p>
   </div>

   <div class="col-12 col-lg">
      <div id="latest_checks">
         <h4>Latest CODECHECKs</h4>
         <ul id="check_list">
         </ul>
      </div>
      <p>See the <a href="/register"><strong>CODECHECK register</strong></a> for all <span id="check_count"></span> completed certificates.</p>
   </div>
</div>

CODECHECK tackles one of the main challenges of computational research by supporting codecheckers with a workflow, guidelines and tools to evaluate computer programs underlying scientific papers.
The independent time-stamped runs conducted by codecheckers will award a _"certificate of executable computation"_ and increase availability, discovery and reproducibility of crucial artefacts for computational sciences.
See [**the CODECHECK paper**](#2021-07--f1000research-paper-on-codecheck-published-after-reviews) for a full description of problems, solutions, and goals and take a look at the [GitHub organisation](https://github.com/codecheckers) for examples of codechecks and the CODECHECK infrastructure and tools.

CODECHECK is based on **five principles** which are described in detail in the [project description](/project) and [the paper](#2021-07--f1000research-paper-on-codecheck-published-after-reviews).

1. Codecheckers record but don’t investigate or fix.
1. Communication between humans is key.
1. Credit is given to codecheckers.
1. Workflows must be auditable.
1. Open by default and transitional by disposition.

**If you want to get involved as a codechecker in the community, or if you want to apply the CODECHECK principles in your journal or conference, please take a look at the [Get Involved](/get-involved) page.**

------

# News

## 2022-09 | CODECHECK Hackathon @ OpenGeoHub Summer School

[Markus](https://www.linkedin.com/in/markus-konkol-a3b244140) [Konkol](https://orcid.org/0000-0001-6651-0976) (<https://github.com/MarkusKonk>, <https://twitter.com/MarkusKonkol>), research software engineer at [52°North](https://52north.org/) and codechecker, organised a **CODECHECK hackathon** as part of the [OpenGeoHub summer school](https://opengeohub.org/summer-school/siegburg-2022/).
He reports on his experiences in a blog post in the 52°North blog at <https://blog.52north.org/2022/09/16/opengeohub-summer-school-facilitating-reproducibility-using-codecheck/>.
It's great to see that codechecking is a suitable evening pastime activity and that participants took some nice learnigns away from the experience of codechecking.
Check out the quotes in the blog post!

Thanks, Markus, for spreading the word about CODECHECK and for introducing more developers and software-developing researchers of the need for their expertise during peer review.

## 2022-06 | AGILE Reproducibility Review 2022

The collaboration between CODECHECK and the AGILE conference series continues!
In 2022, the AGILE conference's [reproducibility committee]() conducted 16 reproductions of conference full papers.
Take a look at the slides presented at the final conference day [here](https://doi.org/10.5281/zenodo.6625206).
The reproducibility review took place after the scientific review.
The reproducibility reports, the AGILE conference's  are published on OSF at <https://osf.io/r5w79/> and listed in the [CODECHECK register](https://codecheck.org.uk/register/).

Learn more about the Reproducible AGILE initiative at <https://reproducible-agile.github.io/>.

[![Reproducible AGILE logo](https://github.com/reproducible-agile/reproducible-agile.github.io/blob/master/public/images/badge/AGILE-reproducible-badge.png?raw=true)](https://reproducible-agile.github.io/)

## 2022-04 | CODECHECK talks

The CODECHECK team is grateful about the continued interest from the research community on the topic of evaluating code and workflows as part of scholarly communication and peer review.

Stephen gave a talk at the [**2022 Toronto Workshop on Reproducibility**](https://canssiontario.utoronto.ca/event/toronto-workshop-on-reproducibility/) organised by [Rohan Alexander](https://rohanalexander.com/).
You can find the [slides online](https://sje30.github.io/talks/2022/codecheck22.html#1) and also watch the [**recording on YouTube**](https://www.youtube.com/watch?v=TgDgcqtsFvE) - very worth a look because of the great Q&A at the end!

Stephen presented **CODECHECK: An Open Science initiative for the independent execution of computations underlying research articles during peer review to improve reproducibility** ([slides](https://bit.ly/codecheck21)) in May 2021 at the [Reproducibility Tea Southhampton](https://reproducibilitea.org/journal-clubs/#Southampton).

Daniel gave the keynote at the [Collaborations Workshop 2022](https://software.ac.uk/cw22) (CW22) on April 4, 2022, organised by the Software Sustainability Institute ([SSI](https://software.ac.uk/)), UK entitled **Code execution during peer review** ([slides](https://bit.ly/cw22-keynote-daniel), [PDF](https://doi.org/10.6084/m9.figshare.19487573), [video](https://youtu.be/EHyEsZCDR1U?t=172)) and presented CODECHECK as well as the partnering initiative [Reproducible AGILE](https://reproducible-agile.github.io/).

## 2021-07 | F1000Research paper on CODECHECK published after reviews

The [F1000Research](https://f1000research.com/) preprint presented below has passed peer review and is now published in version 2.
We are grateful for the two reviewers, [Nicolas P. Rougier](https://orcid.org/0000-0002-6972-589X) and [Sarah Gibson](https://orcid.org/0000-0003-0356-2765), who gave helpful feedback and asked good questions that helped to improve the paper.

> Nüst D and Eglen SJ. **CODECHECK: an Open Science initiative for the independent execution of computations underlying research articles during peer review to improve reproducibility** [version 2; peer review: 2 approved]. F1000Research 2021, 10:253 (<https://doi.org/10.12688/f1000research.51738.2>)
>
> [![screenshot title page of F1000Research paper after peer review](/img/f1000research-paper-2021.jpg)](https://doi.org/10.12688/f1000research.51738.2)

The F1000 blog also features the article with a little Q&A: [https://blog.f1000.com/2021/09/27/codecheck](https://blog.f1000.com/2021/09/27/codecheck).
Thanks [Jessica](https://blog.f1000.com/author/jessicatruschel/) for making that happen!

## 2021-04 | CODECHECK @ ITC

CODECHECK supporter [Markus Konkol](https://twitter.com/MarkusKonkol) has built a CODECHECK process for all researchers at the University of Twente's Faculty of Geo-Information Science and Earth Observation ([ITC](https://www.itc.nl)).
He offers his expertise to codecheck manuscripts and underlying source code and data before submission or preprint publication, so even if the information is still not publicly shared.
His reports will then go public on Zenodo when the paper comes out, just like a regular CODECHECK, and can support the article's claims.
If timed right, authors can even link to the certificate before submission.
_This is a great service for ITC researchers and their reviewers and readers!_

Learn more at **<https://www.itc.nl/research/open-science/codecheck/>** and see an example at <https://doi.org/10.5281/zenodo.5106408>.

## 2021-03 | F1000Research preprint

A preprint about CODECHECK was published at [F1000Research](https://f1000research.com/) and is now subject to open peer review. It presents the codechecking workflow, describes involved roles and stakeholders, presents the _25_ codechecks conducted up to today, and details the experiences and tools that underpin the CODECHECK initiative. We welcome your comments!

> Nüst D and Eglen SJ. **CODECHECK: an Open Science initiative for the independent execution of computations underlying research articles during peer review to improve reproducibility** [version 1; peer review: awaiting peer review]. F1000Research 2021, 10:253 ([https://doi.org/10.12688/f1000research.51738.1](https://doi.org/10.12688/f1000research.51738.1))

## 2020-06 | Nature News article

A [Nature News article](https://doi.org/10.1038/d41586-020-01685-y) by [Dalmeet Singh Chawla](https://www.dalmeets.com/) discussed [the recent CODECHECK `#2020-010`](https://doi.org/10.5281/zenodo.3865491) of a simulation study, including some quotes by CODECHECK Co-PI Stephen J. Eglen and fellow Open Science and Open Software experts [Neil Chue Hong](https://twitter.com/npch) ([Software Sustainability Institute](https://www.software.ac.uk), UK) and [Konrad Hinsen](https://khinsen.net/) (CNRS, France).

> Singh Chawla, D. (2020). **Critiqued coronavirus simulation gets thumbs up from code-checking efforts**. Nature. [https://doi.org/10.1038/d41586-020-01685-y](https://doi.org/10.1038/d41586-020-01685-y)
>
> [![screenshot of Nature News article headline](/img/nature-news-2020.jpg)](https://doi.org/10.1038/d41586-020-01685-y)

## 2019-11 | MUNIN conference presentation

Stephen Eglen presented CODECHECK at [The 14th Munin Conference on Scholarly Publishing 2019](https://site.uit.no/muninconf/).

> Take a look at the [poster](https://septentrio.uit.no/index.php/SCS/article/view/4910/4893) and the [slides](https://septentrio.uit.no/index.php/SCS/article/view/4910/4900), or watch the [video recording](https://mediasite.uit.no/Mediasite/Play/8027873496dc465ebc4b9b3ab0338ad01d?playFrom=1772000).
>
> [![](/img/munin-2019.jpg)](https://mediasite.uit.no/Mediasite/Play/8027873496dc465ebc4b9b3ab0338ad01d?playFrom=1772000)

------

# Follow, share, cite

To stay in touch with the project, follow the [project team](team) members on Twitter:

- [@StephenEglen](https://twitter.com/StephenEglen)
- [@nordholmen](https://twitter.com/nordholmen)

To give a quick overview of the project, feel free to use or extend the [existing slide decks](https://github.com/codecheckers/slides).

To cite CODECHECK in scientific publications, please use the following citation/reference:

> _Eglen, S., & Nüst, D. (2019). CODECHECK: An open-science initiative to facilitate the sharing of computer programs and results presented in scientific publications. Septentrio Conference Series, (1). [https://doi.org/10.7557/5.4910](https://doi.org/10.7557/5.4910)_

<script id="templateCheck" type="x-tmpl-mustache">
{% raw %}
<li>
    <em>"{{title}}"</em><br/>
    <strong><a href="{{link}}" title="CODECHECK report for paper {{title}}">{{link}}</a></strong>
    <br />
    <span class="text-secondary"> Certificate #{{certificate}} | Type: {{type}} | {{datestring}}</span>
</li>
{% endraw %}
</script>

<script type="text/javascript">
$(document).ready(function(){
    var checks = [];
    var stats = {};
    
    $.when(
        $.ajax({
            type: "get",
            url: "https://codecheck.org.uk/register/featured.json",
            dataType: "JSON",
            success: function(data) {
                checks = parseChecks(data);
            },
            error: function(xhr, status) {
                $("#latest_checks").html("<p>Error fetching latest checks.</p>");
            }
        }),
    ).then( function(){
       updateList(checks, 4, "#check_list", "#templateCheck");
    });

    $.when(
        $.ajax({
            type: "get",
            url: "https://codecheck.org.uk/register/stats.json",
            dataType: "JSON",
            success: function(data) {
                stats = data;
            },
            error: function(xhr, status) {
                $("#latest_checks").html("<p>Error fetching latest checks.</p>");
            }
        }),
    ).then( function(){
       updateCount(stats["cert_count"], "#check_count");
    });
});
</script>
