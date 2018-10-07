---
title: Taylor's Careers
permalink: "/careers/"
description: Taylor's Barbershop has several open positions.  Opportunities to be
  a barber, barbering stylist, shop manager and more.
keywords: barbering apprentice, barber careers, barber experience, barbering, beard,
  kids barber, womens barber, shape up, trim, hair color
layout: fullpage
'["//"]': 
bg_header: "/assets/img/header_careers2.jpg"
---

<div class="fullpage_wrapper">
    {%  include components/alpha_header.html
        alpha_header="Careers, We're Hiring"
        alpha_copy="Taylor’s Barbershop is a unique, sleek, upbeat and innovative barbershop space to give you a feel of comfort, fun and relaxation."
    %}

    <!-- Careers Section -->
    <div class="navigation_section career_section">
        <div class="frow justify-between">

            {% for item in site.careers %}
            <div class="career_icon potato">
                <img src="/assets/img/career_icon.png" />
                <div class="career_title">
                    {{ item.career_title }}
                </div>
                <a class="brown_cta" href="{{ site.taylors_job_application }}" target="_blank">
                    <div>
                        apply now
                    </div>
                </a>
            </div>
            {% endfor %}

        </div>

    </div>
</div>
