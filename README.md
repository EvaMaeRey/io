
  - [Welcome and explanation](#welcome-and-explanation)
  - [CV](#cv)
  - [Recent Talks](#recent-talks)
  - [Projects and Goals](#projects-and-goals)
      - [Supporting ‘a new wave of ggplot2
        extenders’](#supporting-a-new-wave-of-ggplot2-extenders)
      - [Supporting newcomers to data visualization and
        ggplot2](#supporting-newcomers-to-data-visualization-and-ggplot2)
      - [Supporting statistical
        learning](#supporting-statistical-learning)
      - [Supporting new R package
        developers](#supporting-new-r-package-developers)
      - [Highlighting new opportuties in viz/ggplot2
        extension](#highlighting-new-opportuties-in-vizggplot2-extension)
          - [Rethinking positional aesthetics (beynod x and
            y)](#rethinking-positional-aesthetics-beynod-x-and-y)
          - [New points of entry as opposed to ggplot(), minimal data
            transformation and/or
            defaults](#new-points-of-entry-as-opposed-to-ggplot-minimal-data-transformation-andor-defaults)
  - [Packages](#packages)
  - [unblogs: experiments and code
    demos](#unblogs-experiments-and-code-demos)
  - [Bio](#bio)

<!-- README.md is generated from README.Rmd. Please edit that file -->

# Welcome and explanation

<!-- badges: start -->

<!-- badges: end -->

‘Do not scatter your energies’,

These days I’m focused a lot on package building. I need a personal
website update update. Instead of trying to reboot my blogdown website
or convert to quarto, I’m just using package building architecture via
pkgdown to create an updated personal webpage.

<!-- I may explore some meta package writing here as well.  -->

# CV

  - [cv](https://evamaerey.github.io/cv/reynolds_evangeline_cv.pdf)
  - [link to update/suggest an
    edit](https://github.com/EvaMaeRey/cv/blob/main/reynolds_evangeline_cv.Rnw)

# Recent Talks

  - [A New Wave of ggplot2 Extenders, at ASA COWY
    chapter](https://evamaerey.github.io/mytidytuesday/2023-09-26-cowy-outline/cowy-outline.html#1)

  - [ggcirclepack and beyond: experiments in the compute\_panel space,
    at ggplot2 extenders,
    Spring 2023](https://evamaerey.github.io/ggcirclepack/circle_pack_and_beyond_talk#1)

  - [Speaking ggplot2, April 2022, West Point Data Analytics
    Series](https://evamaerey.github.io/mytidytuesday/2022-04-21-ggplot2-grammar-primer/ggplot2_grammar_primer.html#1)

  - [Creating new geom\_\*s for richer statistical storytelling,
    May 2022, West Point Department of Mathematics Talk
    Series](https://evamaerey.github.io/mytidytuesday/2022-05-09-statistical-geometries/statistical_geometries.html#2)

  - [Flipbooks, January 2020, RStudio
    Conference](https://youtu.be/9Sgg1lJRM8c?si=Q28CtH59Df8DRmbI&t=408)

  - [Elegant Statistical Narratives with ggxmean: MAA meeting, Poster
    Philidelphia, 2022]()

  - [tidypivot](MAA%20Metro%20New%20York%20May%202022)

  - [Extending ggplot2 statistical geometries, MAA Metro New York
    May 2021](https://evamaerey.github.io/ggxmean/talk_maa_metro_ny.html#1)

  - [Intro to Network Analysis and
    Visualization](https://evamaerey.github.io/mytidytuesday/2022-05-23-networks-presentation/networks_presentation.html#1)

  - [Shallow Fakes: Assessing the potential for spoofing and faking in
    data visualization and what to do about it, University of Denver May
    2019]()

# Projects and Goals

## Supporting ‘a new wave of ggplot2 extenders’

There is a growing population of ggplot2 ‘super-users’ that – given
their regular and long-term ggplot2 use – have a strong working
knowledge of grammar of graphics principles and of ggplot2’s user
interface. Among their ranks are statistics educators, data
visualization professionals, and data scientists and statisticians.

The assertion of this project is that many ggplot2 super-users could
find creating ggplot2 extensions very valuable, but that current
educational materials are falling short in reaching and enabling many in
this group. I’ll then discuss how new material could be tailored to this
group and will introduce some such new points of entry.

<!-- There is a growing population of ggplot2 'super users' that -- given regular and prolonged ggplot2 use -- have a strong working knowledge of the grammar of graphics principles and ggplot2-ic feel and API.  Among the ranks of these super users are statistical educators, data visualization professionals, and seasoned data scientists. -->

<!-- I posit that many folks in this group of super-users could find ggplot2 extension immensely valuable. But that existing materials are falling short in reaching and enabling this group of extraordinary folks in moving into the extension space.   -->

<!-- Specifically, ggplot2 'super users', if provided points of entry tailored to them, would be able to contribute to the ggplot2 extension eco-sphere in thoughtful, grammar-of-graphics-consistent ways.   -->

<!-- And such super-users, are likely to move rapidly into this space given that extension will afford more elegant and efficient workflows. -->

<!-- Investment in ggplot2 extension education for these folks is likely to have many positive externalities.  First, such users are likely to be interested in packaging their materials, providing their elegant and efficient workflow.  This further would strengthen ranks in the R community's package developer base.   -->

<!-- Finally, know-how in the extension space should lead to greater knowledge of the ggplot2 code base and could help build the ggplot2 contributor-maintainer pool of talent. -->

  - easy geom recipes: diving into defining compute\_group ggprotos

  - more geom recipes: cases when compute\_group is not enough
    (compute\_panel)

  - ggtedius workshop

  - Coordinating ggplot2 extenders meetup/support group

## Supporting newcomers to data visualization and ggplot2

  - ggplot2 flipbook
  - a ggplot2 grammar guide

## Supporting statistical learning

  - packages focus on intro stats

  - ma206data with maintained with statistics faculty West Point’s Math

## Supporting new R package developers

  - ggtedius workshop
  - readme2pkg and readme as package story, tocs and enumeration of
    steps SeeEvaMaeRey/ggsmoothfit
  - [A companion guide to Jim Hester’s, ‘You can make an R package in 20
    minutes’](https://evamaerey.github.io/package_in_20_minutes/package_in_20_minutes)

\`Books are meant to be read, … packages are not meant to be read and so
I think it is kind’ - ‘R Packages: Q & A with Jenny Bryan’ around 3:00

## Highlighting new opportuties in viz/ggplot2 extension

### Rethinking positional aesthetics (beynod x and y)

  - aes(fips = my\_fips\_var), e.g ggfips
  - ggcirclepack
  - ggcalendar

### New points of entry as opposed to ggplot(), minimal data transformation and/or defaults

  - ggverbatim()
  - ggedgelist()
  - ggbarlabs()

positional aesthetics

# Packages

<img src="man/figures/README-unnamed-chunk-3-1.png" width="100%" />

# unblogs: experiments and code demos

  - [mytidytuesday lab book](https://evamaerey.github.io/mytidytuesday/)
  - [featurette](https://evamaerey.github.io/featurette/)
  - ggpuzzles: space for untangling gg knots
  - hexes Creating some hex stickers for packages

# Bio

Hello and welcome\! I’m a data scientist and educator that’s especially
passionate about using visualization to facilitate communication and
statistical learning. I’m particularly motivated by the elegance and
power of the “Grammar of Graphics” framework, and am exploring how to
further empower ggplot2 users to take advantage of the extension space
by 1) working on new extension packages for statistical education and 2)
providing new points of entry into the ggplot2 world (tutorials/recipes
as well as community building).

For the last three years, I’ve worked in the Dean’s Data Cell at the
United States Military Academy at West Point in a data analytics and
teaching dual role. I worked closely with stakeholders and other members
of the data team to deliver actionable insights and meet institutional
reporting requirments. I worked on the Deans Data Cell infrastructure
towards, code-first, reproducible and elegant data products. I also
taught sections of MA206 Introduction to Statistics and Probability in
the Mathematics Department, and oversaw five independent studies focused
on tool-building for statistical education (2X Fall AY2022, 1X Spring
AY2022, 2X Spring AY2023).

From Fall AY2018-Spring AY2020, I taught statistical methodology at the
University of Denver’s Josef Korbel School of International Studies
Visiting Teaching Assistant Professor, and previously lectured at the
Technische Universität Dresden’s Center for International Studies
(Spring AY2016 and Spring AY2018). My PhD is from the University of
Illinois, where my dissertation won Burkholder Award for Best
Dissertation in the Political Science Department of the University of
Illinois.

I focus was on international institutions and law especially in the area
of security. More broadly, my areas of study have been International
Relations, Methodology, and Comparative Politics with an emphasis on
Latin American Politics. My dissertation focused on compliance with
supranational law, focusing on the UN Security Council resolutions as my
principle case; I conducted dissertation field research in Brazil in the
Federal House of Deputies.

During my PhD, I worked as a statistics consultant, at the Applied
Technologies of the Arts and Science (ATLAS), at the University of
Illinois from 2013-2015. I also served “Methods TA” in Political Science
in the 2015-2016 academic year at the University of Illinois, providing
assistance and expertise both to undergraduate and graduate students. At
TU Dresden, in 2018, I designed and taught a course introducing students
to data science tools and statistical analysis for political research.

I have been awarded the Fulbright Fellowship (Argentina 2008), Foreign
Language and Area Studies Fellowships (2009-2011), Nelle Signor Travel
Fellowship (Brazil 2011) and have participated in specialized workshops
including the Empirical Implications of Theoretical Models (2010),
Public Policy and Nuclear Threats (2013), the Berkeley Institute for
Transparency in the Social Sciences (2015) workshops, the Zurich Summer
School for Women in Political Methodology (2017), and the Lorentz
Workshop: Empirical Research on International Organizations (2018).

Previously to my academic career, I worked at the U.S. Department of
Commerce’s Bureau of Industry and Security in chemical and biological
export controls and have worked in lithium-ion battery failure
diagnostics at the Chemical Engineering Division of Argonne National
Laboratory.
