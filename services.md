---
title: Taylor's Services
permalink: "/services/"
description: Taylor's Barbering Services + Barbers - Call to make an appointment 804-643-1600
keywords: richmond hair cut, taylors barbershop, taylors hair cut, hot towel shave,
  beard, beard edge, trim, hair color, shampoo
layout: fullpage
'["//"]': 
bg_header: "/assets/img/fullpage-header.jpg"
---

<div class="fullpage_wrapper">
    {%  include components/alpha_header.html
        alpha_header="A full service hair lounge for men, women &amp; kids"
        alpha_copy="Taylor’s Barbershop is a unique, sleek, upbeat and innovative barbershop space to give you a feel of comfort, fun and relaxation."
    %}
</div>

<div class="fullpage_wrapper_alpha">
    <div class="fullpage_wrapper">

        <div class="services_section"  id="services">
            <div class="services_header">barber services</div>

            <ul class="potato">
                <div class="frow justify-between">
                    {% for item in site.services %}
                    <li>
                        {{ item.title }}
                        <div>
                            {{ item.price }}
                        </div>
                    </li>
                    {% endfor %}
                </div>
            </ul>
        </div>
    </div>
</div>

<div class="fullpage_wrapper">
    <div class="barbering_section">

        {%  include components/beta_header.html
            beta_subtitle="schedule your consultation and"
            beta_header="appointment"
        %}

        {%  include components/barbers.html %}

    </div>
</div>

