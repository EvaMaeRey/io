
<!-- README.md is generated from README.Rmd. Please edit that file -->

<br> <br>

# Evangeline ‘Gina’ Reynolds, PhD

Welcome to my website\!

Below you’ll find talk materials, publications and working papers,
software packages, project homepages, and my bio. You can find my CV
[**here**](https://evamaerey.github.io/io/reynolds_evangeline_cv.pdf).
To suggest an edit or update, click
[here](https://github.com/EvaMaeRey/io/blob/main/docs/reynolds_evangeline_cv.rnw).

<!-- badges: start -->

<!-- badges: end -->

<!-- 'Do not scatter your energies',  -->

<!-- These days I'm focused a lot on package building.  I need a personal website update update.  Instead of trying to reboot my blogdown website or convert to quarto, I'm just using package building architecture via pkgdown to create an updated personal webpage.   -->

<!-- I may explore some meta package writing here as well.  -->

# Recent Talks

<!-- [![A mushroom-head robot](/assets/images/codey.jpg 'Codey the Codecademy mascot')](https://codecademy.com) -->

<!-- [![A mushroom-head robot](/docs/title-slide/Untitled.png 'Codey the Codecademy mascot')](https://codecademy.com) -->

<a href="https://evamaerey.github.io/mytidytuesday/2023-09-26-cowy-outline/cowy-slides.html#1" width = "33%"><img src="man/figures/ggplot2_new_wave.png"/></a><a href="https://evamaerey.github.io/mytidytuesday/2022-04-21-ggplot2-grammar-primer/ggplot2_grammar_primer.html#1" width = "33%"><img src="man/figures/primer_wp.png"/></a><a href="https://evamaerey.github.io/mytidytuesday/2022-05-09-statistical-geometries/statistical_geometries.html#1" width = "33%"><img src="man/figures/stats_geoms_wp.png"/></a><a href="https://evamaerey.github.io/tidypivot/maa_may_2022_presentation.html#1" width = "33%"><img src="man/figures/tidypivot_maa.png"/></a><a href="https://evamaerey.github.io/mytidytuesday/2022-05-23-networks-presentation/networks_presentation.html#1" width = "33%"><img src="man/figures/network_du.png"/></a>

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

<a href="https://evamaerey.github.io/mytidytuesday/2022-01-03-easy-geom-recipes/easy_geom_recipes_flipbook.html#1" width = "33%"><img src="man/figures/easy_geom_recipes_flipbook.png"/></a>

  - easy geom recipes: diving into defining compute\_group ggprotos

  - more geom recipes: cases when compute\_group is not enough
    (compute\_panel)

  - ggtedius workshop

  - Coordinating ggplot2 extenders meetup/support group

function (x, file = “data”, ncolumns = if (is.character(x)) 1 else 5,
append = FALSE, sep = " “) cat(x, file = file, sep = c(rep.int(sep,
ncolumns - 1),”"), append = append) \<bytecode: 0x7fc6bc707a90\>
\<environment: namespace:base\>

## Supporting newcomers to data visualization and ggplot2

  - ggplot2 flipbook
  - a ggplot2 grammar guide

## Supporting statistical learning

<a href="https://evamaerey.github.io/ma206distributions" width = "33%"><img src="man/figures/ma206distributions.png"/></a>

  - packages focus on intro stats

  - ma206data with maintained with statistics faculty West Point’s Math

## Supporting new R package developers

## Supporting statistical learning

  - ggtedius workshop

  - readme2pkg and readme as package story, tocs and enumeration of
    steps SeeEvaMaeRey/ggsmoothfit

  - [A companion guide to Jim Hester’s, ‘You can make an R package in 20
    minutes’](https://evamaerey.github.io/package_in_20_minutes/package_in_20_minutes)

  - [immersive companion
    guide](https://evamaerey.github.io/package_in_20_minutes/package_in_20_minutes)

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

[codeexplode](https://github.com/EvaMaeRey/codeexplode),
[codehover](https://github.com/EvaMaeRey/codehover),
[doublecrochet](https://github.com/EvaMaeRey/doublecrochet),
[exampleexploder](https://github.com/EvaMaeRey/exampleexploder),
[formatR](https://github.com/EvaMaeRey/formatR),
[ggbarlabs](https://github.com/EvaMaeRey/ggbarlabs),
[ggbody](https://github.com/EvaMaeRey/ggbody),
[ggbrasil](https://github.com/EvaMaeRey/ggbrasil),
[ggcalendar](https://github.com/EvaMaeRey/ggcalendar),
[ggchile](https://github.com/EvaMaeRey/ggchile),
[ggcirclepack](https://github.com/EvaMaeRey/ggcirclepack),
[ggdirect](https://github.com/EvaMaeRey/ggdirect),
[ggdistrics](https://github.com/EvaMaeRey/ggdistrics),
[ggdistricts](https://github.com/EvaMaeRey/ggdistricts),
[ggextend](https://github.com/EvaMaeRey/ggextend),
[ggfips](https://github.com/EvaMaeRey/ggfips),
[ggjudge](https://github.com/EvaMaeRey/ggjudge),
[ggmemory](https://github.com/EvaMaeRey/ggmemory),
[ggnc](https://github.com/EvaMaeRey/ggnc),
[ggnorthcarolina](https://github.com/EvaMaeRey/ggnorthcarolina),
[ggols](https://github.com/EvaMaeRey/ggols),
[ggpivot](https://github.com/EvaMaeRey/ggpivot),
[ggsample](https://github.com/EvaMaeRey/ggsample),
[ggslice](https://github.com/EvaMaeRey/ggslice),
[ggsmoothfit](https://github.com/EvaMaeRey/ggsmoothfit),
[ggstamp](https://github.com/EvaMaeRey/ggstamp),
[ggstates](https://github.com/EvaMaeRey/ggstates),
[ggverbatim](https://github.com/EvaMaeRey/ggverbatim),
[ggxmean](https://github.com/EvaMaeRey/ggxmean),
[io](https://github.com/EvaMaeRey/io),
[ma206data](https://github.com/EvaMaeRey/ma206data),
[ma206distributions](https://github.com/EvaMaeRey/ma206distributions),
[ma206equations](https://github.com/EvaMaeRey/ma206equations),
[note](https://github.com/EvaMaeRey/note),
[poeml](https://github.com/EvaMaeRey/poeml),
[readme2pkg](https://github.com/EvaMaeRey/readme2pkg),
[tabylextra](https://github.com/EvaMaeRey/tabylextra),
[tidybernoulli](https://github.com/EvaMaeRey/tidybernoulli),
[tidypivot](https://github.com/EvaMaeRey/tidypivot),

# unblogs: experiments and code demos

  - [mytidytuesday lab book](https://evamaerey.github.io/mytidytuesday/)
  - [featurette](https://evamaerey.github.io/featurette/)
  - ggpuzzles: space for untangling gg knots
  - hexes Creating some hex stickers for packages

# Bio

Hello and welcome\! I’m a data scientist, software developer, and
educator who is passionate about using visualization to facilitate
communication about data and in statistical principles. I’m particularly
motivated by the elegance and power of the “Grammar of Graphics”
framework, and am exploring how to further empower ggplot2 users to take
advantage of the extension space by 1) working on new extension packages
for statistical education and 2) providing new points of entry into the
ggplot2 world (tutorials/recipes as well as community building).

For the last three years, I’ve worked in the Dean’s Data Cell at the
United States Military Academy at West Point in a data analytics and
teaching dual role. I worked closely with stakeholders and other members
of the data team to deliver actionable insights and meet institutional
reporting requirements. I worked on the Deans Data Cell infrastructure
towards code-first, reproducible and elegant data products that could be
easily interpreted by a wide audience. I also taught sections of
Introduction to Statistics and Probability (MA206) in the Mathematics
Department, and oversaw five independent studies focused on
tool-building for statistical education (Brown and McGovern in Fall
AY2022, Brown in Spring AY2022, and Folorunso and Jax Spring AY2023).

From Fall AY2018-Spring AY2020, I taught statistical methodology at the
University of Denver’s Korbel School of International Studies. During
this period, I won an R Consortium, which allowed me to work with six
graduate student researchers to advance that project (Granier, Goodman,
Picci, Thapa, Surrency, Woodrum). I had previously lectured at the
Technische Universität Dresden’s Center for International Studies on
international organizations and statistical methodology (Spring AY2016
and Spring AY2018).

My PhD is from the University of Illinois, where my dissertation won
Burkholder Award for Best Dissertation in the Political Science
Department of the University of Illinois. I focus was on international
institutions and law especially in the area of security. More broadly,
my areas of study have been International Relations, Methodology, and
Comparative Politics with an emphasis on Latin American Politics. My
dissertation focused on compliance with supranational law, focusing on
the UN Security Council resolutions as my principle case; I conducted
dissertation field research in Brazil in the Federal House of Deputies.

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
