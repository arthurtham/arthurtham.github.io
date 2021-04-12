---
title: Research
description: Here is what I did in research!
published: true
layout: interest
research:
    self track:
        shorttitle: "Self-tracking Applications"
        id: self-track
        thumbnail: Apps
        description: 
        url: /research/health/
        date: May 2019
    league adverse:
        shorttitle: "Adv. Gameplay in League"
        id: league-adverse
        thumbnail: League
        description: 
        url: /research/league/
        date: March 2020
    know before you go:
        shorttitle: "Know Before You Go"
        id: know-before-you-go
        thumbnail: Know
        description: 
        url: http://www.neerajd.xyz/KnowBeforeYouGo.html
        date: December 2020
    shoppingo:
        shorttitle: "ShoppinGo"
        id: shoppingo
        thumbnail: Shoppingo
        description: 
        url: /research/shoppingo/
        date: March 2021
           
        

---

As an undergraduate researcher in the Health and Information (HAI) lab at UC Irvine and the ICS Honors Program, 
I collaborated on a content analysis of diet, fitness, and Weight Self-Tracking Mobile Apps
on Google Play.

I am currently a member of Team Apps in the Mental Health in Design lab. 

I took a series of research classes at UC Irvine as a graduate student in the M.S. 
Computer Science Program.


<ul class="nav nav-pills">
    <li class="nav-item">
        <a class="nav-link active" data-toggle="tab" href="#researchCollapse">Research Projects</a>
    </li>
    <li class="nav-item">
        <a class="nav-link" data-toggle="tab" href="#organizationsCollapse">Research Groups</a>
    </li>
</ul>
<hr />
<div class="tab-content">
    <div class="tab-pane active" id="researchCollapse">
        <div class="container" style="padding:10px">
            <div class="row">
                <div class="col-sm-12">
                    {% for projectItem in page.research %}
                    {% include research_listing.html %}
                    {% endfor %}
                </div>
            </div>
        </div>
    </div>
    <div class="tab-pane fade" id="organizationsCollapse">
        <div class="container" style="padding:10px">
            <div class="row">
                <div class="col-sm-12">
                    <image src="/img/researchMid.png" /> <br />
                    <image src="/img/researchDBH.png" /> <br />
                    <ul>
                        <li>
                            <a href="https://www.ics.uci.edu/ugrad/honors/program-overview.php" target="_blank">ICS Honors Program </a>
                        </li>
                        <li>
                            <a href="https://hai.ics.uci.edu" 
                            target="_blank">HAI Lab</a>
                        </li>
                        <li>
                            <a href="https://mentalhealthindesign.com/" 
                            target="_blank">MiD Lab</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>




