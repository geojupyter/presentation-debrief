---
title: "🌐 GeoJupyter"
subtitle: |
  💪 Enabling more researchers, educators, and learners to confidently engage with
  geospatial data
title-slide-attributes:
  data-notes: |
    Hi, I'm Matt, and I'll be briefly talking about GeoJupyter, a community which aims
    to enable more researchers, educators, and learners to more confidently interact
    and engage with data about our planet.
format:
  revealjs:
    theme: "white"
    footer: "[Home](/) | [Source](https://github.com/geojupyter/presentation-debrief)"
    auto-stretch: true 
    slide-number: true
---


_TODO: Show video instead?_

![[When our community burned where was the satellite information?](https://www.linkedin.com/pulse/when-our-community-burned-where-satellite-information-pag%C3%A1n-phd-8rxwf/?trackingId=goJI9VniOZAI3RGuoPXysA%3D%3D)](/assets/la-fire-aerial.png)


> ...we are failing the people and causes that need us the most.

-- Brianna R. Pagán, PhD

:::notes
The status quo for working with publicly available geospatial data is that
unfortunately, even very experienced practitioners struggle to leverage data about our
planet when they need it the most.

Dr. Brianna Pagán is a member of the geospatial community that both Fernando and I have
been fortunate to work with and learn from, and we were heartbroken to hear the story of
her loss in the Palisades fire in January this year. Brianna wrote about her experience:

> I should be able to do this. I have a PhD in Remote Sensing, I have built satellite
> data processing pipelines, I help manage one of the NASA satellite data centers, I
> teach courses on climate resilience, adaptation and geoinformatics. [...]  and yet the
> irony is that with all my experience I could not access the information **I knew
> existed** to help our community.

The status quo isn't working, and folks in the geospatial community are deeply aware of
this.
:::

## Approachability is important {.smaller}

::::::columns

:::{.column width=50%}
* Science
    * Climate science
    * Biodiversity
    * Engineering
* Government & policy
    * Decision making
    * Transportation & urban planning
    * Disaster response & hazard management
* Industry
    * Agriculture
    * Logistics
:::

:::{.column width=50%}
![Geospatial data: the "crude oil" of modern science - Image by GPT-4o](/assets/geospatial-data-as-crude-oil.png)
:::

::::::


:::notes
The status quo isn't working, despite the fact that every domain needs geospatial data,
especially organizations fighting for our environment.
We think of geospatial data as the "crude oil" of modern science, and all of these
domains face shared challenges around working with geospatial data.
:::


## Priorietary capture, vendor lock-in, monopoly

::::::columns

:::{.column width=80%}
:stop_sign: Once you're in a proprietary system, the owners' interest is inherently in
keeping you there.

:lock: Proprietary systems are often _not_ interoperable, by design, so you can not freely move your work.

:bug: Proprietary systems are often
[as buggy](https://www.reddit.com/r/ArcGIS/comments/1dp7308/i_feel_like_esri_releases_buggy_af_updates/)
or
[buggier](https://www.google.com/search?q=esri+error+999999)
than open source alternatives.

```text
ERROR 9999999
Something unexpected caused the tool to fail
```
:::

:::{.column width=20%}
![:upside_down_face: Open science with closed software - AGU2023](/assets/open-science-with-arcgis.png)
:::

::::::

:::notes
A major problem in this space is proprietary capture.
Proprietary capture is not just about the money, it's a problem with how we do science.

Often cloud users are enticed with initial ease of use and low costs.

As cloud users continue building in a non-interoperable system, they accumulate inertia,
making it harder to leave.
Additionally, they often discover that they require more services than they initially
assessed, and their costs increase unpredictably over time as it's easier to buy one
more service than it is to migrate.

Sometimes, the proprietary service shuts down, and existing science outputs cease to be
reproducible.

And proprietary systems are often as buggy or buggier than open source alternatives, but
human biases like "sunk cost" cause us to be more forgiving towards software we've paid
for.
Perhaps because of this reduced accountability to their users, proprietary tools also
often offer less respectful error messages than those found in community-owned software.
On screen is a common error message ArcGIS users experience.
:::


## A sustainable community

:::{style="font-size: 1.5rem"}
GeoJupyter's answer to the status quo is a **sustainable** and **self-directing** community.

<br/>

Our community aims to combine the **approachability** and **playfulness** of desktop GIS tools, the
**flexibility** and **reproducibility** of coding-driven GIS methods, and the
**collaborative** and **storytelling** power of Jupyter.
:::

<br/>

Together, we can
[**reimagine geospatial interactive computing**]{style="color: #f37626"}
to enable more researchers, educators, and learners to **confidently engage with
geospatial data**.


## GeoJupyter is... {.smaller}

* 100% open source, modular and interoperable.
* Cloud-native, can run anywhere (laptop, supercomputers, …)
* Capable of:
    * Traditional GIS workloads.
    * Complex, code-driven workflows with earth/planetary data.
    * Leveraging the entire Scientific Python ecosystem.
* AI-ready
* Locally controlled, private, secure
* Vendor agnostic (including commercial AI)
* Led at Berkeley, with US and international partners who are eager


---

:::{.placeholder style="margin: auto; width: 800px; height: 450px; background-color: lightgray; text-align: center"}
Demo GIF
:::


## Closing

:::notes
I've spoken about how this project stands to benefit the world, and I'd like to close by sharing how this work has affected me personally.
Some mornings, I have to remind myself that this project is real and that I'm being supported to work on it.
This mission is important, and I feel privileged to be taking part in it, and to be working with the talented and brilliant folks I am.
Thank you for this wonderful opportunity to grow personally and professionally!

TODO
:::
