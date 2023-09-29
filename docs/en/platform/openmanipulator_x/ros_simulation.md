---
layout: archive
lang: en
ref: openmanipulator_x_ros_simulation
read_time: true
share: true
author_profile: false
permalink: /docs/en/platform/openmanipulator_x/ros_simulation/
tabs: "ROS"
tab_title1: Kinetic
tab_title2: Noetic
tab_title3: Dashing
tab_title4: Foxy
tab_title5: Arduino
sidebar:
  title: "OpenMANIPULATOR-X"
  nav: "openmanipulator_x"
product_group: openmanipulator_x
page_number: 11
---

<div style="counter-reset: h1 6"></div>

{::options parse_block_html="true" /}

# [Simulation](#simulation)

<section data-id="{{ page.tab_title1 }}" class="tab_contents">
{% capture notice_01 %}
**NOTE**:
- Make sure ROS dependencies are installed before performing these instructions
- [Install ROS Packages](/docs/en/platform/openmanipulator_x/quick_start_guide/#install-ros-packages)
{% endcapture %}
<div class="notice--info">{{ notice_01 | markdownify }}</div>
</section>

<section data-id="{{ page.tab_title2 }}" class="tab_contents">
{% capture notice_01 %}
**NOTE**:
- Make sure ROS dependencies are installed before performing these instructions
- [Install ROS Packages](/docs/en/platform/openmanipulator_x/quick_start_guide/#install-ros-packages)
{% endcapture %}
<div class="notice--info">{{ notice_01 | markdownify }}</div>
</section>

<section data-id="{{ page.tab_title3 }}" class="tab_contents">
Gazebo simulation is not supported.  
[https://github.com/ROBOTIS-GIT/open_manipulator_simulations](https://github.com/ROBOTIS-GIT/open_manipulator_simulations)
{: .notice--warning}
</section>

<section data-id="{{ page.tab_title4 }}" class="tab_contents">
Coming Soon (2021 4Q)
{: .notice--success}
</section>

<section data-id="{{ page.tab_title5 }}" class="tab_contents">
Not supported with Arduino
{: .notice--warning}
</section>

## [Launch gazebo](#launch-gazebo)

<section data-id="{{ page.tab_title1 }}" class="tab_contents">
{% include en/platform/openmanipulator_x/simulation/launch_gazebo_kinetic.md %}
</section>

<section data-id="{{ page.tab_title2 }}" class="tab_contents">
{% include en/platform/openmanipulator_x/simulation/launch_gazebo_noetic.md %}
</section>

<section data-id="{{ page.tab_title5 }}" class="tab_contents">
Not supported with Arduino
{: .notice--warning}
</section>

## [Controller for Gazebo](#controller-for-gazebo)

<section data-id="{{ page.tab_title1 }}" class="tab_contents">
{% include en/platform/openmanipulator_x/simulation/gazebo_controller_kinetic.md %}
</section>

<section data-id="{{ page.tab_title2 }}" class="tab_contents">
{% include en/platform/openmanipulator_x/simulation/gazebo_controller_noetic.md %}
</section>

<section data-id="{{ page.tab_title5 }}" class="tab_contents">
Not supported with Arduino
{: .notice--warning}
</section>

## [Operation in Gazebo](#operation-in-gazebo)

<section data-id="{{ page.tab_title1 }}" class="tab_contents">
{% include en/platform/openmanipulator_x/simulation/gazebo_operation_kinetic.md %}
</section>

<section data-id="{{ page.tab_title2 }}" class="tab_contents">
{% include en/platform/openmanipulator_x/simulation/gazebo_operation_noetic.md %}
</section>

<section data-id="{{ page.tab_title5 }}" class="tab_contents">
Not supported with Arduino
{: .notice--warning}
</section>
