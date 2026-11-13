---
layout: splash
title: "Breakthrough Robotics Archive"
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image: /assets/images/ciaraheadline.png
  actions:
    - label: "Visit Breakthrough"
      url: "https://www.breakthrough.org/"
excerpt: "An archive of the Breakthrough FIRST LEGO League team, 2017 to 2022."

hydrodynamics:
  - url: /assets/images/archive/hydro-demo.jpg
    image_path: /assets/images/archive/hydro-demo-th.jpg
    alt: "Team member demoing a robot run"
    title: "Demoing a successful run"
  - url: /assets/images/archive/hydro-robot.jpg
    image_path: /assets/images/archive/hydro-robot-th.jpg
    alt: "Close-up of the Hydrodynamics robot"
    title: "The Hydrodynamics robot"
  - url: /assets/images/archive/kids-working.jpg
    image_path: /assets/images/archive/kids-working-th.jpg
    alt: "Students programming a robot with a coach"
    title: "Programming with a coach"

into_orbit:
  - url: /assets/images/archive/orbit-building.jpg
    image_path: /assets/images/archive/orbit-building-th.jpg
    alt: "Student building with LEGO at bootcamp"
    title: "Summer bootcamp"
  - url: /assets/images/archive/orbit-coach.jpg
    image_path: /assets/images/archive/orbit-coach-th.jpg
    alt: "Coach and student building an attachment"
    title: "Building an attachment"
  - url: /assets/images/archive/orbit-teamwork.jpg
    image_path: /assets/images/archive/orbit-teamwork-th.jpg
    alt: "Students talking through a plan"
    title: "Teamwork"
  - url: /assets/images/archive/orbit-poster.jpg
    image_path: /assets/images/archive/orbit-poster-th.jpg
    alt: "Into Orbit season poster"
    title: "Into Orbit"

city_shaper:
  - url: /assets/images/archive/city-model.jpg
    image_path: /assets/images/archive/city-model-th.jpg
    alt: "Students holding a mission model"
    title: "Building mission models"
  - url: /assets/images/archive/city-table.jpg
    image_path: /assets/images/archive/city-table-th.jpg
    alt: "The City Shaper game table"
    title: "Setting up the game table"
  - url: /assets/images/archive/city-crane.jpg
    image_path: /assets/images/archive/city-crane-th.jpg
    alt: "The crane mission model"
    title: "The crane mission"
  - url: /assets/images/archive/city-kanban-making.jpg
    image_path: /assets/images/archive/city-kanban-making-th.jpg
    alt: "Students making a Kanban board"
    title: "Making the Kanban board"
  - url: /assets/images/archive/city-kanban-board.jpg
    image_path: /assets/images/archive/city-kanban-board-th.jpg
    alt: "The finished Kanban board"
    title: "Sprint planning"
  - url: /assets/images/archive/city-litter-cycle.jpg
    image_path: /assets/images/archive/city-litter-cycle-th.jpg
    alt: "Hand-drawn diagram of the litter cycle"
    title: "Innovation Project: the litter cycle"

cargo_connect:
  - url: /assets/images/archive/cargo-spike.jpg
    image_path: /assets/images/archive/cargo-spike-th.jpg
    alt: "Students building with SPIKE Prime"
    title: "Building with SPIKE Prime"
---

<div class="notice--info" markdown="1">
**This site is an archive.** The Breakthrough Robotics team site is no longer updated, and the
schedules, sign-ups, and forms that used to live here have been retired. To learn about
Breakthrough's current programs, get involved, or volunteer, please visit
[breakthrough.org](https://www.breakthrough.org/).

[Visit Breakthrough](https://www.breakthrough.org/){: .btn .btn--primary}
</div>

## About the team

From 2017 to 2022, the Breakthrough Robotics team competed in
[FIRST LEGO League](https://www.firstlegoleague.org/) alongside other Chicago-area
schools and clubs. Each fall, students built and programmed a LEGO robot to tackle the
season's Robot Game, researched a real-world problem for the Innovation Project, and
practiced the FIRST Core Values: discovery, innovation, impact, inclusion, teamwork, and fun.
As FIRST puts it, we don't use kids to build robots; we use robots to build kids.

Thank you to every student, family, coach, and volunteer who made it happen.

## Photos {#photos}

### Hydrodynamics (2017-18)

{% include gallery id="hydrodynamics" %}

### Into Orbit (2018-19)

{% include gallery id="into_orbit" caption="Season details: [Into Orbit](/season2018)" %}

### City Shaper (2019-20)

{% include gallery id="city_shaper" %}

### Cargo Connect (2021-22)

{% include gallery id="cargo_connect" caption="Season details: [Cargo Connect](/season2021)" %}

## Blog

Notes from the coaches over the years, kept here as they were written.

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>({{ post.date | date: "%B %Y" }})</small></li>
{% endfor %}
</ul>
